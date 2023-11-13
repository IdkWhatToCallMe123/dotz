# Dotz

![Untitled](Untitled.png)

# ⚠️ HEADS UP!!!!! ⚠️

Some of the extensions and the theme are incompatible/broken on the latest GNOME version (GNOME 45)

************************PLEASE DON’T UPDATE TO THE LATEST GNOME VERSION IF YOU WANNA USE THIS SETUP!!!************************

THAT ALSO MEANS DON’T UPGRADE TO THE LATEST FEDORA VERSION OR THE LATEST UBUNTU VERSION AS THEY BOTH USE THE GNOME 45

## A tiny message before the actual tutorial (im sorry)

### THIS PAGE IS NOWHERE DONE!!!!!

also:

If you feel like anything is lacking or unclear, don’t hesitate to ask me! I also constantly struggle with installing stuff my self cuz im fat idiot.

**Also to the more seasoned linux users:** I don’t really know much coding or how to write these dot file page-whatevers. I use linux mainly because i have apps that I like that works better/only on Linux and also because windows is a buggy and laggy mess.

If you have some feedback on how i can improve stuff pls lemme know

# Quick chip and bits:

Theme:  [https://github.com/catppuccin/gtk](https://github.com/catppuccin/gtk)

(I personally used Macchiato-Standard-Red)

Icons: [https://github.com/PapirusDevelopmentTeam/papirus-icon-theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) plus [https://github.com/catppuccin/papirus-folders](https://github.com/catppuccin/papirus-folders)

Fetch: [https://github.com/ssleert/nitch](https://github.com/ssleert/nitch)

# Necessary GNOME extensions:

- [https://extensions.gnome.org/extension/5338/aylurs-widgets/](https://extensions.gnome.org/extension/5338/aylurs-widgets/)
- [https://extensions.gnome.org/extension/3193/blur-my-shell/](https://extensions.gnome.org/extension/3193/blur-my-shell/)
- [https://extensions.gnome.org/extension/3843/just-perfection/](https://extensions.gnome.org/extension/3843/just-perfection/)
- [https://extensions.gnome.org/extension/4928/mpris-label/](https://extensions.gnome.org/extension/4928/mpris-label/)
- [https://extensions.gnome.org/extension/750/openweather/](https://extensions.gnome.org/extension/750/openweather/)
- [https://extensions.gnome.org/extension/3906/remove-app-menu/](https://extensions.gnome.org/extension/3906/remove-app-menu/)[https://extensions.gnome.org/extension/2986/runcat/](https://extensions.gnome.org/extension/2986/runcat/)
- [https://extensions.gnome.org/extension/5489/search-light/](https://extensions.gnome.org/extension/5489/search-light/)
- [https://extensions.gnome.org/extension/19/user-themes/](https://extensions.gnome.org/extension/19/user-themes/)
- [https://extensions.gnome.org/extension/1460/vitals/](https://extensions.gnome.org/extension/1460/vitals/)

## The extensions that require a bit of extra configuration:

### Aylur’s widgets

Turn on these 

- Battery bar (With “Show Icon” disabled)
- Dynamic panel (Be sure to enable “Floating”)
- Power Menu
- Quick settings:

**Show System Levels:** Off

**Style:** Normal

**Media player:** 

Style**:** Full 

Cover Width: 500

Cover Height: 170

<aside>
💡 Extra note:
I disabled the Stylish on screen display as it broke some OSD popups from some other extension I use

</aside>

### Blur My Shell

1. Turn **********************everything********************** off except for application blur.
2. Add your desired apps to the list (In my case it was only the terminal)
    
    Note: Since the “Add Window” is kinda broken (at least for me), we have to manually figure out what the application that we wanna blur is called.
    
    - If your application is installed through you package manager:
        
        List your installed packages (google it if you don’t know how to) and find the name of your application, then paste it into Blur My Shell (I think it’s done this way idk since was too lazy to try this, tell me if it doesn’t work)
        
    - If your application is installed through Flatpak:
        
        Find your app on [https://flathub.org](https://flathub.org) and click on the drop-down arrow next to the Install button. Copy the last part of the command (doesn’t matter which one) and paste it into Blur My Shell!
        
    - If your application is installed through Snap:
        
        Idk how to do it bc i dont use snap oops pls tell me if you know how to do it and ill put it here :)
        

<aside>
💡 Extra note:

I set my opacity to 178 as I think it was the best balance between readability and cool-nes

</aside>

### Just Perfection

- Hide the power/battery icon
- Notification position → Top End
- Date/time → To The Right

 

### Mpris label

- Position → Extension place → Left
- Album art scaling → 60
- Under the **Label** tab → Hide the album in **********Visible fields and order**********

### OpenWeather

- Position in panel → Left

### Search Light

- Border radius → Turn it up a bit until it looks good
- Background color → use the picker tool and pick the UI background in the popup windows

### Spacebar

- Position in top panel → Center

<aside>
💡 - To rename your workspaces/desktops right click on the menu in the top bar. If you wanna use emojis use this: [https://flathub.org/sv/apps/it.mijorus.smile](https://flathub.org/sv/apps/it.mijorus.smile)

</aside>

# How to spice up the terminal

1. Install a little bit of this: [https://github.com/fish-shell/fish-shell](https://github.com/fish-shell/fish-shell)

<aside>
💡 To make fish your default shell follow this guide: [https://askubuntu.com/a/26459](https://askubuntu.com/a/26459)
*Also not all commands in fish are exactly the same as in Bash. If you encounter any trouble you can just start Bash in your terminal and continue there*

</aside>

1. Then pepper a bit of this: [https://github.com/oh-my-fish/oh-my-fish](https://github.com/oh-my-fish/oh-my-fish)
2. Then make it cool with this: h[ttps://github.com/catppuccin/fish](https://github.com/catppuccin/fish)
3. To get the ****************E P I C**************** icons install a font of your choice: [https://www.nerdfonts.com/](https://www.nerdfonts.com/)
    
    (I personally used FiraCode :D)
    
4. Install Black Box (the terminal app) 
    
    link: [https://flathub.org/sv/apps/com.raggesilver.BlackBox](https://flathub.org/sv/apps/com.raggesilver.BlackBox)
    
5. Toggle these:
    - General → Header Bar → Show Header Bar → ******OFF******
    - General → Header Bar → Floating Controls → Show Floating Controls: ****ON****
    - Terminal → Terminal → Padding → 10
6. To install the theme:
    
    1.  Download one of these: [https://github.com/catppuccin/tilix/tree/main/src](https://github.com/catppuccin/tilix/tree/main/src)
    
    1. Under Terminal→Theme click the folder icon
    2. Copy the previously downloaded .JSON file and put it in the ******************Schemes****************** folder
    3. Restart ****************Black Box****************
    4. Navigate back to the theme settings and select your theme
    5. Assuming you configured **********************Blur My Shell**********************  properly (mentioned in the previous section) your terminal should look something like this now:
    
    ![Untitled](Untitled1.png)
    

## Extra stuff

working on it
