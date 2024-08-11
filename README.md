![logo](https://raw.githubusercontent.com/youpie/Folder_icon_creator/main/data/icons/nl.emphisia.icon.svg)

# Iconic 📁

Iconic lets you easily add images on top of a folder icon. It is mostly meant for Gnome. 
This application is my first attempt at creating an application using Rust and Libadwaita.

<a href='https://flathub.org/apps/details/nl.emphisia.icon'><img width='240' alt='Get it on Flathub' src='https://flathub.org/api/badge?locale=en&light'/></a>

![afbeelding](https://github.com/youpie/Iconic/blob/main/data/screenshots/Main%20screen%20dark.png?raw=true)

## Todo 📝
These are ideas I want to implement.
- [X] Create Icon*
- [ ] Add features
    - [X] Automatically load the folder Icon*
    - [X] Support SVG's*
    - [X] Drag and drop
    - [ ] Proper error handling
    - [X] Add threading
        - [X] Loading images*
            - [ ] Loading dragged images
        - [X] Saving images*
        - [ ] Making images monochrome
    - [X] Start Screen
    - [ ] Export to SVG
    - [X] Change folder image in preferences
    - [X] Add warning if closing with unsaved changes*
    - [X] Convert top image to Greyscale*
        - [X] Slider for threshhold
        - [X] Select color* 
    - [X] Add key shortcuts*
        - [X] Save
        - [X] Open 
    - [ ] Rounded corner option for top image
    - [X] Load image folder on start*
    - [X] Ability to save and load settings
    - [X] Add ability to temporarily change folder icon*
    - [X] Loading symbolic icons directly
        - [ ] Add symbolic icon picker (like [Icon Library](https://gitlab.gnome.org/World/design/icon-library))
    - [X] Automatically place icon in right position
    - [ ] Add guide grid or something
    - [ ] Ability to directly set image of folder (if even possible)
        - [ ] Ability to drag generated image from iconic window to nautulis  
- [ ] Clean up code
- [ ] Add comments
- [X] Correct flatpak manifest*
- [X] Think of better name
- [ ] Add dontation link :)

## Contributing 🤝
This program is mostly meant as practise for me so I want to solve most problems by myself. So the best will be to create an issue if you encounter any.
If you want to create a merge request. That is off course totally fine, but please try not to fundamentally change how it works and clearly explain what you did and how it works 😁

## Running the app 🏃
If you want to run the app:
1. Clone the repo
2. Open it in [gnome-builder](https://flathub.org/apps/org.gnome.Builder)
3. Start the application by pressing `ctrl+shift+escape`

## Credits 🫂
Wow documentation is really hard to understand so I used few programs as inspiration and to learn how everything works, so massive shout-out to:
- Eyedropper - https://github.com/FineFindus/eyedropper
- Switcheroo - https://gitlab.com/adhami3310/Switcheroo
- Geopard - https://github.com/ranfdev/Geopard
- Obfuscate - https://gitlab.gnome.org/World/obfuscate
- Loupe - https://gitlab.gnome.org/GNOME/loupe

## Icon credits
The icon is just a few already existing icons added together, the following are used:
- Gnome text editor - https://gitlab.gnome.org/GNOME/gnome-text-editor
- Adwaita icons - https://gitlab.gnome.org/GNOME/adwaita-icon-theme
