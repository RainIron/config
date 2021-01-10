# Arch设置(i3-wm)
### Pacman包

```
修改国内源：/etc/pacman.d/mirrorlist
Server = https://mirrors.163.com/archlinux/$repo/os/$arch
Server = https://mirrors.tuna.tsinghua.edu.cn/archlinux/$repo/os/$arch
Server = https://mirrors.aliyun.com/archlinux/$repo/os/$arch

添加archlinuxcn：/etc/pacman.conf
[archlinuxcn]
SigLevel = Optional TrustAll
Server = http://mirrors.163.com/archlinux-cn/$arch
```

- xorg和xorg-server
- i3-wm、i3status和i3lock
- feh
- compton
- Git
- nautilus
- LightDM



### AUR包

```
修改yay源：
# yay --aururl "https://aur.tuna.tsinghua.edu.cn" --save
```

- typora
- lightdm-slick-greeter









