# SMMO chat client - windows software
### You can now support me through [Patreon](https://www.patreon.com/y0mu)
## Latest Version: [0.9.3-beta](https://bit.ly/3ra5das)


![Chat Client image](https://github.com/ImY0mu/SMMO-chat/blob/master/chat.png)
### Features:
- Custom themes -> option to add, remove, customize, export or import themes
- Chat commands
- Window priority over other windows
- Profanity filter
- Player menu when clicked on name in chat
- Guild menu to navigate to guild pages when clicked on guild name
- Game menu to navigate to game pages when clicked on gamepad button in right side menu (top right icon)
- Emoji keyboard
- SOFT updating - chat does not get automatically updated if you are not scrolled to top
   - notification showing how many new messages are there since the last update -> updates chat on click
- Tag feature -> history of tags & windows notifications when tagged
### Requirements:
- Windows OS
### Installation guide:
1. Download and install. 
#### You may receive warning from Windows -> I am too poor to buy Windows certificate

## Patch notes
#### 0.9.3-beta
- Fixed typo mistake
- Fixed Windows notifications
- Fixed resizing issue when window was minimalized with window priority enabled
- Fixed bug when NULL tooltip showed up on icon click
- Improved and added new chat commands (/commands)
- Removed quick game links (guild name, player name, gamepad) - all are part of commands

#### 0.9.2-beta
- UI changes
- NEW FEATURE - Commands [write /commands into chatbox and press send to find out more] - suggestions for new commands are welcome
- Added new tooltips (hover over icons in names)
- Fixed caret placement when picked emoji
- Fixed game's staff action menu and tags
- Fixed invert chat bug
- Preparation for 1.0

#### 0.9.0-beta
- App is now more smooth: Authentication, Chat and Logout are now handled in different instances
- Changed emoji keyboard library
- Guild chat can be found in channels from now
- Added 3 new context menu -> Click at your name, your guild name or at the new gamepad icon in side menu
- Common rarity color gets lighter if your background color is dark
- New Feature - Tags history
- New Feature - Windows notification when tagged and window is in background (let me know if it does not work for you)
- Fixed some item rarity colors not showing up in chat
- Made some changes to context menu
- Changed the way help is shown in settings
- Preparation for 1.0

#### 0.8.6-beta
- Fixed tagging and player menu of names containing [ & ] after name
- Fixed item rarity colors not showing up at item popup
- Fixed some item rarity colors not showing up in chat
- Made some changed to patch notes (again)
- You can now redirect to player market from item popup and search for the item
- Moderators can now mute within the app
- Changed the textarea for send message
- F5 now refreshes the chat & starts the autoupdating in case of server dying
- Changed position of Christmas lights bcs of long names
- Removed some information from popups for Background, Avatar, Sprite
- Changed position, size and made some design changes to player menu
#### 0.8.5-beta
- Fixed event trigger
- Fixed styling mistakes at patch notes
- Fixed styling mistakes at settings and updated name and the description of each option - Thanks Synn
- Fixed send item option - used to redirect to attack page
- Patch notes and About popups have fixed colour theme
- Added an option to send gold within the app -> error messages not included bcs of limitations
- Client switches between light & dark theme on installation, it depends on your windows prefered settings
- You can now refresh the client by F5 or CTRL+R
#### 0.8.2-beta
- Rewrote few functions
- Implemented new chat channels -> trade, support
- Implemented latest patch notes
- Many changes and fixes of UI
- Fixed auto updating
- Halloween theme!
- Changed few variables for theme customization 
##### If you have a custom theme, it is recommended to export and import your customized theme so it fully works
#### 0.7.4-beta
- Fixed context menu for long names
- Fixed bugs after Mike's changes to chat API (send message, server message, not working context menu items, etc.)
- Changed position of event type icon at server message (from chest, ba)
#### 0.7.0-beta
- Reworked context menu (Action menu)
- Refresh/send button is now disabled when the chat is updating
- Moved to the game's CHAT API server -> should be a lil bit faster
- Changed guild icon at the change chat button
- Reworked auto update interface
#### 0.6.4-beta
- hotfix of being stuck at blank screen 
#### 0.6.2-beta
- Small UI changes
- Added new options to Player Action menu (Gift diamonds, View Market)
- Added new feature "Quick Action" -> Set which you would like to use in settings (Usage: Shift + Left Click on player's name)
- Added new feature "Chat Flow" -> Set which you would like to use in settings (Reverses the flow of chat [Top -> Bottom] | [Bottom -> Top])
