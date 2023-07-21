# TOTKDowngrade-1.2.0-Save-version
Downgrade Game update and Game save to play TOTK on 1.1.1 in stock FW

DISCLAIMER: Optional steps below may or may not result to a ban so do this at your own risk. I haven't found a guide so I made an effort to make this. 

Needed:
1. JKSV backup of 1.1.2/1.2.0 save
2. TOTK cartridge 
3. TOTK 1.1.1 NSP 391MB file (I used "TLOZ-TOTK-(USA)-NSwTcH-NSP-Update111-Ziperto")
4. Save the nsp file in the nsp folder in root or wherever
5. CFW switch on 16.0.3
6. Optional: Clean unhacked switch

  A. Downgrade your Save Game version from 1.2.0 to 1.0 (so that game will not force you to download update when used):
1. Using CFW switch in emunand, 
2. Remove existing 1.2.0 totk installation (maybe use tinfoil).
3. In Emunand while offline, insert TOTK cartridge and dont install update.
4. Restore the 1.2.0 game save using JKSV and play the game. yes 1.0.0 TOTK will load 1.2.0 save just fine. :)
5. When game save is Loaded, save the game. This will convert that save slot to version 1.0 save!
6. Do this with all the slot by teleporting to sky, overworld, underground alternately while letting it autosave and do a hard save. Do this couple of times to overwrite all save slots with auto save and hard saves using the 1.0 version of the game.
7. Use JKSV to backup this new save game using a different name. 

  B. Update your CFW sysndand switch with 1.1.1 Game Version:
1. In your CFW switch, Boot CFW to clean sysnand offline
2. Disable Auto software udpate in System
3. Plug TOTK cartridge and dont update (if you removed it)
4. Use Goldleaf to update game using the 1.1.1 file
5. Tun off auto update

   C. Play downgraded save in Stock FW
1. Boot up to CFW sysnand
2. Use JKSV to restore downgraded save from Section A on your sysnand
3. Reboot to Stock FW and play the game
   
  D. OPTIONAL: Send 1.1.1 game update to a clean unmodded switch: I used two cartridge for eah switch. Not sure if it will work on one cart only.
1. If you want to play TOTK in a different switch, Reset factory settings that device to wipe TOTK game updates. Don't sync it yet with your Account, just create a user. Keep offline.
2. turn  the CFW switch (from section B) to sysndand 
3. turn on Clean switch, Turn off auto update
4. Use match version feature to install the 1.1.1 update to your clean switch. While game is selected, press + and under Software Update, use Match Version with Local Users feature.

E. OPTIONAL: Sync to Cloud save and play on your Clean 2nd console
1. Boot your CFW switch to Stock FW
2. Link the user account to your Nintendo account (You can get a ban if you have other pirated stuff on your CFW switch!)
3. Upload your save to Cloud Backup (error may show up saying Server save does not match local save until unified...etc)
4. Ignore error and Upload your save and overwrite your online save
5. From your clean switch, link your existing user to Your nintendo account
6. Download that 1.1.1 Cloud save
7. Turn off auto backup and internet in CFW switch
8. Recheck that auto back up and update in Clean switch is OFF
9. Enjoy!
