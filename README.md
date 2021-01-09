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

