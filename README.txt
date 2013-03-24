(c) 2013 by Cydh - house.bad@gmail.com

-----------------------------------
-- Special Customs by Cydh --------
-----------------------------------
Every custom that has conf files, look at conf/battle/mod_cydh.conf
1. Separate Pick Log Tables - Look at log database on MySQL
	- conf file: yes
2. Zeny From Mobs Adjusment - Adjust gained zeny from mobs as like you want, just like adjust item drop rates
	- conf file: yes
	- db/mob_zeny_db.txt
	- Edit @rates and @mobinfo
3. Delay2UseItem - Delay (in miliseconds) to use item after using skill
	- conf file: yes
	- conf/mapflag/delay2useitem.txt
	- db/item_delay.txt
4. Noconsume Mapflag - Prevent player to use item consumable item at noconsume maps
	- conf file: yes
	- conf/mapflag/noconsume.txt
5. Noequip Mapflag - Prevent player to wear any equipments at noconsume maps
	- conf file: yes
	- conf/mapflag/noequip.txt
6. Maxcap! - Give maximum damage when player attacking
	- conf file: yes
	- conf/groups.conf - Set group permission to bypass this maxcap mode
	- conf/mapflag/maxcap.txt
	- db/skill_maxcap_db.txt
7. @refine Prevention - Prevent certain Group Level (conf/groups.conf) to instant refine item use @refine or @item2
	- conf file: yes
	- db/item_no_atrefine.txt
8. @item Prevention - Prevent certain Group Level (conf/groups.conf) to get item by using @item command
	- db/item_no_atitem.txt
9. Warp Delay - Give delay to player that attempts to escape when attacking or receiving attack.
	- conf file: yes
10. AFK Mapflag - @afk command only can be used at afk maps
	- conf file: yes
	- conf/mapflag/afk.txt
11. Homunculus EXP Rates - Adjust EXP gained for Homunculus just like base_exp_rate and job_exp_rate
	- conf file: yes
	- conf/mapflag/nohomexp.txt (another mapflag 'hexp' works just like 'hexp' and 'jexp')
	- db/mob_homun_exp.txt
	- @showhomexp - Show homunculus EXP that gained after killing mobs
	- Edit @rates and @mobinfo
12. [BETA Test] Damage Adjustments - Adjust global damage rates, like PK damages on (conf/battle/misc.conf), GVG (conf/battle/guild.conf), and Battleground (conf/battle/battleground.conf)
	- conf file: yes
	- conf/mapflag/atk_rate.txt
13. @aura1/@aura2 - Set additional aura for player. (Originally from eAthena old forum)
	- @aura1 <number>
	- @aura2 <number>
	- Support 2 auras.
14. Custom Broadcast Color - Broadcast font color using @broadcast or @localbroadcast depending on Group Level
	- db/custom_broadcast_color.txt
	- @reloadpcdb - Reload color database [Cydh]
16. Advanced countitem() Script Command - Now can use countitem() to count certain item in cart, storage, or guild storage too. Also works for countitem2()
	- Look at doc/script_commands.txt
17. Advanced delitem() Script Command - Now can use delitem() to count certain item in cart, storage, or guild storage too. Also works for delitem2()
	- Look at doc/script_commands.txt
18. Security System - Secure your items
	- @security
19. Lock Player Atcommand - Prevent player to disable atcommand, so when player using every atcommand it will shows like normal chat.
	- @lockcommand "<char name>" is used to lock or unlock
	- lockcommand() is used to lock player atcommand by NPC script
	- unlockcommand() is used to unlock by NPC script
	- checklockcommand() is used to check the status by NPC script. 1 = locked, 0 = unlocked
20. Drop Player Item - Drop certain item with certain amount from player inventory
	- @dropitem <item id> <amount>
	- @dropitem "<item name>" <amount>
21. Store Items to Guild Storage - Instanly store all inventory items to guild storage, but must open guild storage at least once then close it first
	- @gstoreall
22. Put All Equipment Off - Put all equipments off intantly (all equipments from ALT+Q to inventory)
	- @unequipall
23. Away Message - Makes auto reply for whisper/incoming PM
	- @away "<message>"
24. AFK - Log off the account but makes the character left AFK in-game
	- @afk "<chat room title>" - makes char AFK with chat room
	- @afk2 "<away message>" - makes char AFK with Notice Board hat + away message (@away)
25. Autostore Looted Items - Store all looted items to storage automatically without open the storage
	- @autostore <item type> {<min. char weight>}
26. Intravision - Gives player intravision (Maya Purple Effect) without Maya Purple Card
	- @intravision
	- conf/groups.conf - Set group's permission to get Intravision instanlt for all player in certain group
27. Taming Monster Skill - Sage's skill -Taming Monster- becomes custom skill for Super Novice classes
28. bonus bNoEleStone - Custom item bonus that allow player use skill without Flame, Water, Wind Stone, and Shadow Orb
	- doc/item_bonus
29. Global Damage Adjustment - Set global damage rate for short and long attack damage, also weapon, magic, and misc skill damage
	- conf file: yes

-----------------------------------
-- Another Customs ----------------
-----------------------------------
1. Chat Color - Chat color that appears to another player can be customized depends on Group Level
	- db/chat_color_db.txt
	- @reloadchatcolor - reload color database [Cydh]
2. Manage Damage Skill - Adjust damage for skills
	- db/skill_damage_db.txt
3. Find Vended Items - Find item that sell in buyingstore by other players easily
	- @whosell
4. Auraset - Set additional aura for player. (Originally from eAthena old forum) [Modified by Cydh] 
5. 