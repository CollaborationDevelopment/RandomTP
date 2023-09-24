How To Setup:
1. You need to install Luckperm, Deluxe Menus, PlaceHolderApi And Random Wil Teleport
2. Drag the 3 plugins in ur plugins folder and start your server
3. open Deluxe Menus folder in the plugin folder and drag randomtp.yml to the gui_menus folder
4. after that go back to ur Deluxe Menus folder and open config.yml
5. Copy And Paste this on ur config.yml
debug: HIGHEST
check_updates: true
gui_menus:
  randomtp:
    file: randomtp.yml

if you only want to add the file in the config just paste
  randomtp:
    file: randomtp.yml

6. in your minecraft game or console type /lp group defualt permission set deluxemenus.default.rtp true
7. After that restart your server and boom there you have it!