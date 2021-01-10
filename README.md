# ArchLinux and i3wm Configuration

### China mirrors

```
# vim /etc/pacman.d/mirrorlist
Server = https://mirrors.163.com/archlinux/$repo/os/$arch
Server = https://mirrors.tuna.tsinghua.edu.cn/archlinux/$repo/os/$arch
Server = https://mirrors.aliyun.com/archlinux/$repo/os/$arch

# vim /etc/pacman.conf
[archlinuxcn]
SigLevel = Optional TrustAll
Server = http://mirrors.163.com/archlinux-cn/$arch

```

### Pacman Package

- xorg and xorg-server
- i3-wm, i3status and i3lock
- feh
- picom
- git
- nautilus
- firefox
- lightdm
-  xorg-server-xephyr
- 



### Yay Package

```
edit configuration
# yay --aururl "https://aur.tuna.tsinghua.edu.cn" --save
```

- typora
- lightdm-slick-greeter
- google-chrome
- 