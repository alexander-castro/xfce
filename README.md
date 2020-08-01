# Personalize xfce

- Install Chrome
https://www.google.com/chrome/

- Plank

`sudo add-apt-repository ppa:docky-core/stable`
`sudo apt-get update`
`sudo apt-get install plank`

`plank --preferences`

Theme: Transparent
Icon size: 64
Icon Zoom: On

Settings -> Session and Startup > Application Autostart (Add plank)

- Theme Nordic
`sudo apt install git`
`git clone https://github.com/EliverLara/Nordic.git`
Copy folder Nordic in /usr/share/themes/

Settings -> Aparence -> Style -> Nordic
Settings -> Windows Manager -> Style -> Nordic

- Icons Tela

`git clone https://github.com/vinceliuice/Tela-icon-theme.git`
`cd Tela-icon-theme`
`./install.sh`
Settings -> Aparence -> Icons -> Tela Dark

- Terminal colors

`git clone https://github.com/arcticicestudio/nord-xfce-terminal.git`
`cd nord-xfce-terminal`
`./install.sh`
Terminal -> Edit -> Preferences -> Colors -> Presets -> Nord

- Launcher 
https://ulauncher.io/
Theme: Elementary Dark
