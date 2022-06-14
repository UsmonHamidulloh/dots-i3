<p align="center">
  <img src="https://github.com/UsmonHamidulloh/i3wm-dotfiles/blob/main/image.png?raw=true">
</p>

- <b>Operatsion tizim:</b> ArchLinux
- <b>Shell:</b> fish (oh my fish)
- <b>WM</b>: i3
- <b>Shirft:</b> JetbrainsMono Nerd fonts + DejaVu Sans Mono

<h3>Kerakli package'larni o'rnatish (arch/arch-based):</h3>

```
sudo pacman -Syyu
sudo pacman -S alacritty
sudo pacman -S feh
yay -S polybar
yay -S picom-ibhagwan-git
```

<h3>Kerakli shirftlarni o'rnatish (arch/arch-based):</h3>

```
yay -S nerd-fonts-dejavu-complete
yay -S nerd-fonts-jetbrains-mono
```

<h3>O'rnatish:</h3>
  
```
git clone https://github.com/UsmonHamidulloh/i3wm-dotfiles
cd i3wm-dotfiles/
cp -r alacritty/ ~/.config/
cp -r i3/ ~/.config/
cp -r polybar/ ~/.config/   
cp -r wallpaper/ ~/.config/
cp picom.conf ~/.config/
```
