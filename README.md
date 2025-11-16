## Waybar Themes for linux

 A collection of my Waybar themes – have fun exploring and customizing them!

## Instructions

My Waybar configurations from V1 to V2.1 used additional packages such as wttrbar and waybar-cava.
However, I no longer use these modules. If someone still wants to use them, they can simply install the missing packages.

For basic functionality, it is enough to copy only the config.jsonc and style.css files.

Everything else is optional add-ons, such as the waybar-pacman module to display incoming updates<br>

```bash
  yay -S waybar-module-pacman-updates-git
```
    
## Screenshots V1
- No hyprland/window / pacman/update module / no screenrecord button stop <br>
##### V1 Install-command (copy and paste in your terminal): <br>
```bash
git clone https://github.com/HANCORE-linux/waybar-themes.git /tmp/repo && cp -rf /tmp/repo/config/v1/. ~/.config/waybar && rm -rf /tmp/repo && omarchy-restart-waybar
```
<img width="2560" height="1440" alt="screenshot-2025-09-07_18-38-28" src="https://github.com/user-attachments/assets/16c8b398-d1b3-4519-bcbe-e15ad920c7ff" />

## Screenshots V2
- added pacman/arch update module & added hyprland/window module <br>
##### V2 Install-command (copy and paste in your terminal): <br>
```bash
git clone https://github.com/HANCORE-linux/waybar-themes.git /tmp/repo && cp -rf /tmp/repo/config/v2/. ~/.config/waybar && rm -rf /tmp/repo && omarchy-restart-waybar
```
<img width="2560" height="1440" alt="screenshot-2025-09-08_00-34-55" src="https://github.com/user-attachments/assets/5cdbb695-83fa-47ec-9271-95dbe4691ffe" />

## Screenshots V2.1
- added screenrecord button stop with new Omarchy Update 3.0.1 to waybar config & style <br>
- removed hyprland/window module <br>
##### V2.1 Install-command (copy and paste in your terminal): <br>
```bash
git clone https://github.com/HANCORE-linux/waybar-themes.git /tmp/repo && cp -rf /tmp/repo/config/v2.1/. ~/.config/waybar && rm -rf /tmp/repo && omarchy-restart-waybar
```
<img width="300" height="54" alt="screenshot-2025-09-18_22-45-54" src="https://github.com/user-attachments/assets/aa13ae41-6d40-407e-bbe8-cc04c5ff2124" />

## Screenshots V3
- new waybar Style (without red accents)
- base config is from https://github.com/CobyPowers/omarchy/tree/master/config/waybar (Credits goes to https://github.com/CobyPowers ) , i added some functions according to my needs and changed the high <br>
##### V3 Install-command (copy and paste in your terminal): <br>
```bash
git clone https://github.com/HANCORE-linux/waybar-themes.git /tmp/repo && cp -rf /tmp/repo/config/v3/. ~/.config/waybar && rm -rf /tmp/repo && omarchy-restart-waybar
```
<img width="1310" height="209" alt="screenshot-2025-11-07_12-03-43" src="https://github.com/user-attachments/assets/852ce3fe-f2d0-4b2b-b7da-3ad0e4b79e4c" />


## Screenshots V3 (shadow)
- all shadow , waybar and tooltip
##### V3-shadow Install-command (copy and paste in your terminal): <br>
```bash
git clone https://github.com/HANCORE-linux/waybar-themes.git /tmp/repo && cp -rf /tmp/repo/config/V3-shadow/. ~/.config/waybar && rm -rf /tmp/repo && omarchy-restart-waybar
```
<img width="1307" height="209" alt="screenshot-2025-11-07_11-41-49" src="https://github.com/user-attachments/assets/1b804243-5249-4181-bcc1-558be83d8e18" />


## Screenshots V4
- new waybar style with base config from V3 - please backup your config & style file before applying <br>
- module informations: leftside (omarchy-menu, workspaces, hyprland/window) center (clock, idle_inhibtor, omarchy-update, recording) rightside (packman-updates and the rest) <br>
- Contributions & Credits to [Adso](https://github.com/adsovetzky/Adso-dotfiles) for helping to finish this :) <br>
##### V4 Install-command (copy and paste in your terminal): <br>
```bash
git clone https://github.com/HANCORE-linux/waybar-themes.git /tmp/repo && cp -rf /tmp/repo/config/V4/. ~/.config/waybar && rm -rf /tmp/repo && omarchy-restart-waybar
```
<img width="1341" height="48" alt="screenshot-2025-11-04_17-41-45" src="https://github.com/user-attachments/assets/a607fd2b-fd91-412b-83b0-afbb2c16c5d7" />
<img width="2560" height="1440" alt="screenshot-2025-11-04_17-41-21" src="https://github.com/user-attachments/assets/3b71d778-360c-49ce-aa45-788a4a995955" />



## Screenshot V4 (slim)
- less hight than basic V4<br>
##### V4-slim Install-command (copy and paste in your terminal): <br>
```bash
git clone https://github.com/HANCORE-linux/waybar-themes.git /tmp/repo && cp -rf /tmp/repo/config/V4-slim/. ~/.config/waybar && rm -rf /tmp/repo && omarchy-restart-waybar
```
<img width="1298" height="925" alt="screenshot-2025-11-04_23-32-53" src="https://github.com/user-attachments/assets/0d2c5f3e-8416-44ee-9a9a-8148bbb8177c" />

## Screenshot V5 (solo bars)
- trying something new<br>
##### V5-solo Install-command (copy and paste in your terminal): <br>
```bash
git clone https://github.com/HANCORE-linux/waybar-themes.git /tmp/repo && cp -rf /tmp/repo/config/V5-solo/. ~/.config/waybar && rm -rf /tmp/repo && omarchy-restart-waybar
```
<img width="2560" height="1440" alt="screenshot-2025-11-14_14-17-18" src="https://github.com/user-attachments/assets/691322cc-2fa4-4665-a14f-02a3a8d24b14" />

## Screenshot V5.b
- trying something new.b<br>
##### V5.b Install-command (copy and paste in your terminal): <br>
```bash
git clone https://github.com/HANCORE-linux/waybar-themes.git /tmp/repo && cp -rf /tmp/repo/config/V5.b/. ~/.config/waybar && rm -rf /tmp/repo && omarchy-restart-waybar
```
<img width="1520" height="42" alt="screenshot-2025-11-14_14-34-00" src="https://github.com/user-attachments/assets/871f25a4-dc74-4e0b-a321-f73a2cd148bd" />
<img width="1920" height="1080" alt="screenshot-2025-11-14_23-18-39" src="https://github.com/user-attachments/assets/7e92e1c3-3d09-40d7-9703-95d7b21a14f1" />


## Screenshot V6 
- Original version by [Adso](https://github.com/adsovetzky/Adso-dotfiles), adapted by me to fit my needs and style<br>
- Shadow effects in the text field, icons, and page margins<br>
- length of waybar can be adjust in config.jsonc and change the "width" value to your needs
##### V6 Install-command (copy and paste in your terminal): <br>
```bash
git clone https://github.com/HANCORE-linux/waybar-themes.git /tmp/repo && cp -rf /tmp/repo/config/V6/. ~/.config/waybar && rm -rf /tmp/repo && omarchy-restart-waybar
```
- <img width="1264" height="803" alt="screenshot-2025-11-12_00-03-51" src="https://github.com/user-attachments/assets/56eb8a58-fc05-4634-9671-c9e8f5e8f9fe" />
<img width="1264" height="547" alt="screenshot-2025-11-12_00-08-38" src="https://github.com/user-attachments/assets/7e5a2728-31bc-4ae3-9367-05c7f6dcc856" />

## Screenshot V6.b 
- less hight and added border-radius<br>
##### V6.b Install-command (copy and paste in your terminal): <br>
```bash
git clone https://github.com/HANCORE-linux/waybar-themes.git /tmp/repo && cp -rf /tmp/repo/config/V6.b/. ~/.config/waybar && rm -rf /tmp/repo && omarchy-restart-waybar
```
  <img width="1323" height="512" alt="screenshot-2025-11-12_19-23-18" src="https://github.com/user-attachments/assets/e5d01188-9c93-4a5b-8a16-fe8bc370e2d9" />




