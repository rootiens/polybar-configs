<!-- Polybar Themes-->

![image](https://user-images.githubusercontent.com/24958462/124374637-51d2f000-dcb2-11eb-82cc-d80288d17e99.png)


##

### Dependencies

Install following programs on your system before you use these themes.

- **`Polybar`** : Ofcourse, the bar itself
- **`Rofi`** : For App launcher, network, power and style menus
- **`pywal`** : For pywal support
- **`calc`** : For random colors support
- **`networkmanager_dmenu`** : For network modules

### Fonts

Here's a list of all fonts used by these themes.

**`Text Fonts`**
- Iosevka Nerd Font
- Fantasque Sans Mono
- Noto Sans
- Droid Sans
- Terminus

**`Icon Fonts`**
- Iosevka Nerd Font
- Icomoon Feather
- Material Icons
- Waffle (Siji)

### Installation

Follow the steps below to install these themes on your system.

- First, Clone this repository -
```
$ git clone --depth=1 https://github.com/adi1090x/polybar-themes.git
```

- Change to cloned directory and make setup.sh executable -
```
$ cd polybar-themes
$ chmod +x setup.sh
```

- Run `setup.sh` and select a style -
```
$ ./setup.sh

[*] Installing Polybar Themes...

[*] Choose Style -
[1] Simple
[2] Bitmap

[?] Select Option : 1

[*] Installing fonts...
[*] Creating a backup of your polybar configs...
[*] Successfully Installed.
```

- That's it, These themes are now installed on your system.

> Note : These themes are like an ecosystem, everything here is connected with each other in some way. So... before modifying anything by your own, make sure you know what you are doing.

### Launch the bar

To launch the bar with the selected theme, Just...

- Open the terminal and enter the following command - 
```
$ bash ~/.config/polybar/launch.sh

Usage : launch.sh --theme

Available Themes :
--blocks    --colorblocks    --cuts      --docky
--forest    --grayblocks     --hack      --material
--panels    --pwidgets       --shades    --shapes
```

- Now, select your theme and launch the bar - 
```
$ bash ~/.config/polybar/launch.sh --forest
```
