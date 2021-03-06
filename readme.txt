LATEST RELEASED VERSION
====================================================
[Google Play Store](https://play.google.com/store/apps/details?id=com.erakk.lnreader)

DEVELOPMENT REQUIREMENT:
====================================================
* Android SDK
* eclipse Juno + ADT
* JSoup 1.7.2
* ActionBarSherlock
* Android 3+ (Honeycomb)

APPLICATION REQUIREMENT:
====================================================
* Recommended Android 3.0+ (API Level 11)
* Minimum     Android 2.2  (API Level 8)
* Some features might not working if running below the recommended version.

LINE-ENDINGS & SOURCE ENCODING CONFIG
====================================================
* Git Config:
  - https://help.github.com/articles/dealing-with-line-endings
  - https://stackoverflow.com/questions/1889559/git-diff-to-ignore-m
* Eclipse Config:
  - http://stackoverflow.com/questions/1886185/eclipse-and-windows-newlines

FAQ
====================================================
Q1: I cannot load the Main Novel List/empty novel list!
A1: Try to disable the AdBlocker/Firewall.

Q2: The last updated date is showing 43 years ago!
A2: Try to disable the AdBlocker/Firewall.

(Old Version 20130106)
TASK LIST - Version 1.1.0 beta build 31
====================================================
//DONE
- inverted default VolumeRocker scroll direction.
- Removed annoying sound when using VolumeRocker.
- Database backup/restore implemented
- Downloads intent+++ Make it cooler
- anti sleep function 
- Fix volume buttons when not in scroll mode
- Unit steps for scrolling Volume Rocker 1 = 100 normalized
- make bookmarks accessible in every part of the app
- Download all info make a background task
- Reformatted last update/check text
- Jump to inside content layout fixed
- Bookmarks screen fix layout
- fix novel content headers/titles
- Fixed an issue where only the last updated novel was notified
- Add update service to download list.
- Add status message in download list.
- Add download List too all intents
- Remove Downloads and from main menu, add them as popup menu.
- Rename ImageActivity to something better
- Add Orignal Light Novels List
- Teaser and Original list to use Download List Model
- Clicking an undownloaded chapter will add it to the download list if it hasn't been downloaded.
- Added more visual tips about novel states "Read", "Has Update" and "External"
- Novels, Teasers and Original novels lists are all shown under "Light Novels", separated by tabs.
- Added option to enable auto downloading an undownloaded chapter on the download list
- added "Go Top" and "Go Bottom" to chapter menu
- preloading all lists on the tab activity
- "download XXX novels" instead of "complete novel"
- Add Update History Activity
- Consolidate updates into single notification
- Fix formatDateForDisplay() bug
- Refactor some Util method.
- Fix issue #20: Infinite Loading for Empty Watch List
- FIx too many update notification problem - Impolemented Notification Screen
- Home button (mascot) on download list not working
- Webview Dynamic buttons first implementation
- Remove asyncTaskCount from settings
- Added options menu in Novels lists
- Fixed database location issues

//CRASH FIXES
- Fixed a crash that would occur if trying to unbind an unregistered service on low memory warning.
- Fixed a crash that related to scrolling while reading a novel.

//TODO
- Manual Add Crash fix
- Tabs not showing correctly on Android ver 2.2 - 2.3.7
- Light Novel List / Main Menu Layouts
<low priority/>
- Add first time Tutorial for new users to show off functionalities, skipable. // May go to next version only, or will be added later.
- EULA/BT Copyrights on first time run // Need to prepare a EULA.
- Manual add series tutorial for new users


//TODO NEXT VERSION ONLY
- let finished downloads stay unless deleted*

maybe ill add an option to "remove complete downloads automatically" for those who dont like removing manually...

//NEEDS RETHINKING/CHECKING
- Reduce image download message sizes on download list
- make external chapters open in an internal customized webview (not all externals open the same way?)
- Verify clicking mascot in chapter and going to jump to screen.
- Make lightNovel list download a download list task
- When loading main page for first time, add message "found x novel series" lowPriority

this mascot (is the icon on the upper left, only shows on newer android versions, like a back button) bug is not checked yet.

//FUTURE IDEAS
- Advanced Customization options
- Integration with external cloud apps for image/database saving:
> DropBox
> Box
> Skydrive
> Google Drive
> This is just an IDEA, and as such, not to worry for now.



ANDROID PERMISSION LIST
====================================================
* android.permission.ACCESS_NETWORK_STATE
  - For checking internet state.
* android.permission.INTERNET
  - For downloading data from Baka Tsuki.
* android.permission.WRITE_EXTERNAL_STORAGE
  - For saving image cache.
* android.permission.READ_EXTERNAL_STORAGE
  - For reading image cache.
* android.permission.VIBRATE
  - For notification.
