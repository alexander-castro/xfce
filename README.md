# Personalize xfce

- Install Chrome
https://www.google.com/chrome/
-Visual Studio Code
https://go.microsoft.com/fwlink/?LinkID=760868

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
Font: Ubuntu

- Terminal colors

`git clone https://github.com/arcticicestudio/nord-xfce-terminal.git`
`cd nord-xfce-terminal`
`./install.sh`
Terminal -> Edit -> Preferences -> Colors -> Presets -> Nord

- Terminal zsh- ohMyZsh
`sudo apt-get install zsh -y`
`sh -c "$(wget https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"`
`git clone https://github.com/powerline/fonts.git --depth=1`
`cd fonts`
`./install.sh`

`git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
`git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`
Font: Source code pro - 11

- Launcher 
https://ulauncher.io/
Theme: Elementary Dark

- Wallpaper
https://wallhaven.cc/w/2em38y
