# Yaru-Stone Theme

A modified version of the **Yaru-olive** GTK theme, with all greens replaced by greys — providing a neutral color option that Yaru doesn’t include by default.
A matching icon theme that's a mashup of the Yaru-sage theme and the outdated gray theme from https://github.com/Jannomag/Yaru-Colors. I replaced as many icons as possible with the gray ones and left the rest as sage, since sage is the closest color to grey.

## Requirements

* The **yaru-theme-gtk** package must be installed prior to using this color extension for the GTK theme.
* The **yaru-theme-icon** package must be installed prior using this color extension for the icon theme.
* The **Yaru-stone-icons** theme must be installed prior to using the **Yaru-stone-dark-icons** theme.
  
  _This is because the dark icons theme is just an index.theme file that inherits the icons from the light theme. Its only purpose is to allow desktop envirements to automatically set the Yaru-stone-dark GTK theme when it's selected, and vice-versa. Xfce doesn't have an option for automatically matching themes and icons so it's useless for Xfce._
  

## Installation

1. **Download and unzip** the theme folders from the releases page.
2. **Move** the extracted folders to the system theme directories using the following commands:

   ```bash
   sudo mv Downloads/Yaru-stone /usr/share/themes
   ```

   ```bash
   sudo mv Downloads/Yaru-stone-dark /usr/share/themes
   ```

    ```bash
   sudo mv Downloads/Yaru-stone-icons /usr/share/icons
   ```
    
   ```bash
   sudo mv Downloads/Yaru-stone-dark-icons /usr/share/icons
   ```

## Recommended Window Manager Themes

This theme pairs well with the following **xfwm4** themes:

* **Daloa**
* **Kokodi**





* Tested on **Debian 13 (Xfce 4.20)**.
