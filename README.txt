(c) 2012 ~ 2013 by Cydh - house.bad@gmail.com
http://pservero.com

*******************************************************************
-------------------------------------------------------------------
//////////////////////// PAID MODIFICATION ////////////////////////
/////////////////// Pay for each modification /////////////////////
////////////////// Current Total Value: 510 USD ///////////////////
-------------------------------------------------------------------
*******************************************************************
Every custom that has conf files, look at conf/battle/mod_cydh.conf!
1. Maxcap! - Give maximum damage when player attacking
	- 40 USD
	- conf file: yes
	- conf/groups.conf - Set group permission to bypass this maxcap mode
	- npc/mapflag/maxcap.txt
	- db/skill_maxcap_db.txt
	- [Info]
		- Default maxcap: default maxcap damage for all skills if skill's maxcap doesn't specified on db/skill_maxcap_db.txt
		- Default normal attack: non-skill damages have maxcap againts player, mob, boss, and other
		- Defualt normal attack for EDP and (Maximum) Overthrust: non-skill damages have different damage if player has this buff
2. Separate Pick Log Tables - Look at log database on MySQL	[Requested by Zack]
	- 20 USD
	- conf file: yes
	- MySQL file: separate_logs_db.sql
	- [Info]
		- Separate 'picklog' table to several table logs based on enable_logs's ack that decided on log_athena.conf
3. Security System - Secure your items from transaction
	- 30 USD (+5 USD for additional ack)
	- @security - Custom atcommand to manage the security system
	- NPC file: Security.txt
	- [Info]
		- Prevent unlocked security to:
		  . Ask trade request to other
		  . Receive trade request from other
		  . Sell item on NPC
		  . Buy item from NPC
		  . Open vending
		  . Buy item from vender
		  . Open buyingstore
		  . Sell item to buyer
		  . Compound card (additional ack)
		  . Remove (set off) option from ALT+Q (additional ack)
		  . Using skill that need zeny (additional ack)
		  . Consume usable item (additional ack)
		- GM (player with certain group level) can manage the global config
4. Autostore Looted Items - Store all looted items to storage automatically without open the storage
	- 15 USD
	- @autostore <item type> {<min. char weight>}
	- [Info]
		- Item type is defined in bitmask: 1 - Useable item, 2 - Equipment, 4 - Etc Item, 8 - Card
5. @storage2 - Open other player's storage
	- 15 USD (becomes 20 USD if you desire with @partnerstorage)
	- @storage2 <char name>
	- [Info]
		- Only certain GM level can use this
		- Can do whatever like open the own storage
		- The target can't open and do any changes when GM accesses his/her storage
6. @partnerstorage - Open partner's storage
	- 15 USD (becomes 20 USD if you desire with @storage2)
	- @partnerstorage
	- [Info]
		- Only for marrigae player, so they can handle the partner's torage whatever he/she wants
		- The target can't open and do any changes when partner accesses his/her storage
7. Chat Color - Chat color that appears to another player can be customized depends on Group Level	[Requested by Zack]
	- 5 USD
	- db/chat_color_db.txt
	- @reloadchatcolor - reload color database [Cydh]
	- [Info]
		- Specified group level will show different color from normal chat color
8. Getitemslots2 Script Command - Get number of item slots that edited by Epoque's Expansion Pack	[Requested by Zack]
	- 10 USD
	- NPC file: getitemslots2.txt
	- [Info]
		- Official 'getitemslots' script command can't get the real slot of add/remove slot by Epoque
9. Homunculus Damage Ignorance - Makes homunculus ignores any incoming damage	[Requested by Judas] [Improved by CandyCandy's request]
	- 20 USD
	- conf file: yes
	- @homimmune <immune type>
	- npc/mapflag/hom_ignorance.txt
	- [Info]
		- Immunity type makes homun immune from: 1 - damage, 2 - status change, 3 - both
10. Homunculus Modification - Another homunculus modification, more creation mode [Requested by CandyCandy]
	- 30 USD
	- conf file: yes
	- [Info]
		- Feeding success chance
		- Hide/temporary remove when hungry
		- Hungry delay rate
		- Loot when hungry
		- Master will not loot when idle
11. Deathmatch PVP - PVP likes Counter-Strike Deathmatch game	[Requested by Farhan]
	- 15 USD, include all script commands that needed
	- [Info]
		- This is an auto PVP game, the most killer will be winner. Dead player will be respawned at PVP map for fighting until the end!
12. bSkillEle,n,x,y - Makes single attack skill has chance to has specified element when hit [Requested by Vince de Vera of DareDevilRO]
	 - 10 USD
	 - n is Skill Name, x is Element, y is Chance in percent
13. Character ScriptBonus - Give specified character get { Script } bonus [Requested by Vince de Vera of DareDevilRO]
	- 20 USD
	- NPC files are included
	- [Info]
		- The bonuses are stored on table, and will be loaded when calculating pc status
		- { Script } is based on doc/item_bonus.txt
14. Experience Distance Share - Give max. distance for party member when receiving shared EXP [Requested by gintoki]
	- 10 USD
	- conf file: yes
	- [Info]
		- If party member is far away from decided distance, he/she will not receive any EXP
15. MVP Walkable Distance - Makes MVP can walk away from its spawn point [Requested by gintoki]
	- 10 USD
	- conf file: yes
	- [Info]
		- If MVP walk away from its spawn point, it will be rewarped with full HP
		- MVP doesn't move from their point if no enemy is around
16. Permanent Flooritem - Allows player makes flooritem that can be cleaned by @cleanmap [Requested by Jham Ash]
	- 5 USD
	- @flooritem <item_id> <amount>
	- conf file: yes
	- [Info]
		- The items only can be cleaned by @cleanflooritem
17. Destroy global item - Delete all specified item on online players [Requested by Jham Ash]
	- 10 USD
	- @destroyitem <item_id>
	- @destroycartitem <item_id>
	- @destroystorageitem <item_id>
	- @destroysqlitem <item_id>
	- [Info]
		- All specifed item will be deleted
		- If using @destroysqlitem, it will delete from storage, guild storage, cart, and inventory from all players
18. Delay2UseItem - Delay (in miliseconds) to use item after using skill
	- 10 USD
	- conf file: yes
	- npc/mapflag/delay2useitem.txt
	- db/item_delay.txt
	- [Info]
		- Gives delay after using specified skill to specified enemy
19. Immortal Item [Requested by Zack]
	- 15 USD
20. Force Drop Item [Requested by Zack]
	- 15 USD
21. Weapon Level System [Requested by Zack]
	- 25 USD
22. Monster of The Month [Requested by Rasyid Razak]
	- 25 USD
23. Angry Monsters [Requested by Rasyid Razak]
	- 20 USD
24. Warewolf system [Requested by Patrick Lopez Escalona]
	- 15 USD
25. Manacle system [Requested by Patrick Lopez Escalona]
	- 15 USD
26. Fixed PVP Cell system [Requested by RealRO]
	- 20 USD
27. Additional Item Bonus [Requested by ]
	- 25 USD
	- db/item_bonus_additional.txt
	- [Info]
		- Specified equip can has additional script bonus
28. Combine Equip [Requested by ]
	- 25 USD
	- NPC included
	- [Info]
		- Can combine 2 equips, and the primary equip will get all script effect from second equip
29. Advanced Vending Tax [Requested by ]
	- 20 USD
	- NPC included
	- [Info]
		- Specified map can has vending tax, and the map owner (guild) can get the tax


*******************************************************************
-------------------------------------------------------------------
//////////////////////// FREE MODIFICATION ////////////////////////
/////////////////////// Get this freely!! /////////////////////////
-------------------------------------------------------------------
*******************************************************************
1. Zeny From Mobs Adjusment
	- conf file: yes
	- db/mob_zeny_db.txt
	- Edit @rates and @mobinfo
	- [Info]
		- Adjust gained zeny from mobs as like you want, just like adjust item drop rates
2. Noconsume Mapflag
	- conf file: yes
	- npc/mapflag/noconsume.txt
	- [Info]
		- Prevent player to use item consumable item at noconsume maps
3. Noequip Mapflag
	- conf file: yes
	- npc/mapflag/noequip.txt
	- [Info]
		- Prevent player to wear any equipments at noconsume maps
4. @refine Prevention
	- conf file: yes
	- db/item_no_atrefine.txt
	- Usage on @refine, @item2
	- [Info]
		- Prevent certain Group Level (conf/groups.conf) to refine specified item use @refine or @item2
5. @item Prevention
	- db/item_no_atitem.txt
	- Usage on @item
	- [Info]
		- Prevent certain Group Level (conf/groups.conf) to get specified item by using @item command
6. Run delay on battle
	- conf file: yes
	- [Info]
		- Give delay to player that attempts to escape when: attacking, receiving damage, or by using skills.
		- Can decide only add the delay of the enemy is: player, monster, pet, homunculus, or merc (basic conf NOTE 3)
7. Global Damage Adjustment
	- conf file: yes
	- npc/mapflag/atk_rate.txt - Adjust damage rate at certain map
	- [Info]
		- Set global damage rate for short and long attack damage, also weapon, magic, and misc skill damage
8. Homunculus EXP Rates
	- conf file: yes
	- conf/mapflag/nohomexp.txt (another mapflag 'hexp' works just like 'hexp' and 'jexp')
	- db/mob_homun_exp.txt
	- @showhomexp - Show homunculus EXP that gained after killing mobs
	- Edit @rates and @mobinfo
	- [Info]
		- Adjust EXP gained for Homunculus just like base_exp_rate and job_exp_rate		
9. Auraset
	- @aura1 <number>
	- @aura2 <number>
	- [Info]
		- Set additional aura for player. (Originally from eAthena old forum)
		- Added specified script effect for specified aura number
10. Custom Broadcast Color
	- db/custom_broadcast_color.txt
	- @reloadpcdb - Reload color database [Cydh]
	- [Info]
		- Broadcast font color using @broadcast or @localbroadcast depending on Group Level
11. Advanced countitem() Script Command
	- Look at doc/script_commands.txt
	- @countitem <item_id>
	- @cartcountitem <item_id>
	- @storagecountitem <item_id>
	- [Info]
		- Now can use countitem() to count certain item in cart, storage, or guild storage too. Also works for countitem2()
12. Advanced delitem() Script Command
	- Look at doc/script_commands.txt
	- @cartdelitem <item_id> <amount>
	- @storagedelitem <item_id> <amount>
	- [Info]
		- Now can use delitem() to count certain item in cart, storage, or guild storage too. Also works for delitem2()
13. Lock Player Atcommand
	- @lockcommand "<char name>" is used to lock or unlock
	- script command: lockcommand() is used to lock player atcommand by NPC script
	- script command: unlockcommand() is used to unlock by NPC script
	- script command: checklockcommand() is used to check the status by NPC script. 1 = locked, 0 = unlocked
	- [Info]
		- Prevent player to disable atcommand, so when player using every atcommand it will shows like normal chat.
		- There is option to svae the locked state as permanent char variable
14. Drop Player Item
	- @dropitem <item id> <amount>
	- @dropitem "<item name>" <amount>
	- [Info]
		- Drop certain item with certain amount from player inventory
15. Store Items to Guild Storage
	- @gstoreall
	- [Info]
		- Instanly store all inventory items to guild storage, but must open guild storage at least once then close it first
16. Put All Equipment Off
	- @unequipall
	- [Info]
		- Put all equipments off intantly (all equipments from ALT+Q to inventory)
17. Away Message
	- @away "<message>"
	- [Info]
		- Makes auto reply for whisper/incoming PM
18. AFK
	- @afk "<chat room title>" - makes char AFK with chat room
	- @afk2 "<away message>" - makes char AFK with Notice Board hat + away message (@away)
	- npc/mapflag/afk.txt
	- [Info]
		- Log off the account but makes the character left AFK in-game
		- Mapflag works like autotrade mapflag
19. Intravision
	- @intravision
	- conf/groups.conf - Set group's permission to get Intravision instanlt for all player in certain group
	- [Info]
		- Gives player intravision (Maya Purple Effect) without Maya Purple Card
		- NOTE: Actually can use OnPCLogin
20. Map Announcer
	- conf file: yes
	- db/map_desc.txt
	- [Info]
		- Announces map description to player self every map changed
21. Refine Bonus
	- db/refine_bonus.txt
	- [Info]
		- Give more additional bonus for refined equipment, just like Script on item_db.txt
22. Map Warp Exceptions
	- script command: mapwarpexcept <"from map_name">,<"to map_name">,<to x>,<to y>,<AccountID>{,<CharVariableName>}
	- [Info]
		- Warp all players at specified map with exception
23. Get Highest Variable Value
	- script command: gethighestvalue <"CharVariableName">{,<Location>};
	- [Info]
		- Return highest value of player variables at specified map and variable name
24. Get Attached IDs
	- script command: getattachedids <Type>,"<CharVariableName>"{,"<MAP_NAME>"}
	- [Info]
		- Return 2 array of attached IDs from specified variable and map
25. Freeze Map
	- script command: freezemap {<"mapname">}{,<monsterignore '1'>};
	- script command: unfreezemap {<"mapname">}{,<monsterignore '1'>};
	- [Info]
		- Makes players freeze at specified map

*******************************************************************
-------------------------------------------------------------------
////////////////////////// SERVER FEATURES ////////////////////////
-------------------------------------------------------------------
*******************************************************************
-----------------------------------
-- Added from Paid Modification ---
-----------------------------------
** All from PAID MODIFICATIONs **

-----------------------------------
-- Added from Free Modification ---
-----------------------------------
** All from FREE MODIFICATIONs **

-----------------------------------
-- Another Customs ----------------
-----------------------------------
1. Manage Damage Skill
	- db/skill_damage_db.txt
	- npc/mapflag/skill_damage.txt	[Cydh]
	- [Info]
		- Adjust damage for specified skills
2. Find Vended Items
	- @whosell
	- [Info]
		- Find item that sell by oper players on vending
3. Find Beeing Bought Items
	- @whosell
	- [Info]
		- Find item that beeing bought by other player on buyingstore
-----------------------------------
-- Misc ---------------------------
-----------------------------------
1. Taming Monster Skill - Sage's skill -Taming Monster- becomes custom skill for Super Novice classes

