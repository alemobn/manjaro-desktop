![Demo 01](docs/demo.png)

**Run Base Script**

`git clone https://github.com/alemobn/manjaro-desktop.git`

`chmod +x ./manjaro-desktop/script.sh && ./manjaro-desktop/script.sh`

**Breeze Cursor Install**

`sudo pacman -S breeze`

**CBlack Theme Install**

`git clone https://github.com/Cloweling/cblack.git`

`cd cblack && make install`

`cd .. && rm -rf cblack`

**Kora Icon Install**

`git clone https://github.com/bikass/kora.git`

`mkdir ~/.icons && mv kora/kora ~/.icons`

`rm -rf kora`

**Grub Theme Install**

`git clone --depth 1 https://gitlab.com/VandalByte/dedsec-grub-theme.git && cd dedsec-grub-theme
sudo python3 dedsec-theme.py --install`

`cd .. && rm -rf dedsec-grub-theme`

**BlackBox Prompt Install**

`flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo`

`flatpak install flathub com.raggesilver.BlackBox`

**Other Features**

- Transparent panel extension
- Jetbrains mono terminal font
- Minimal cinnamon animations
- Text scale 1.1x
- Bash or Fish shell
- Minimal menu icons
- Panel height 46px (full hd resolution)