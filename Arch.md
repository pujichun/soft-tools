记录我在arch上使用的软件，有时间补充一些小众的软件的详细的配置和使用方法

<!--more-->

#### yay

拉取`AUR`中的软件，项目地址：https://github.com/Jguer/yay

#### neovim

```shell
sudo pacman -S neovim
```

更快的vim，学会了vim再也不想使用其他编辑器了，就是调试不方便，补全插件使用`coc.nvim`，coc项目地址：https://github.com/neoclide/coc.nvim

#### google-chrome

```shell
yay -S google-chrome
```

#### visual-studio-code-bin

```shell
yay -S visual-studio-code-bin
```

有的东西用neovim不方便的时候用一下，在Linux上轻松半透明

#### LibreOffice

```shell
sudo pacman -S liberoffice liberoffice-fresh-zh-cn
```

Linux上的办公软件，功能也是十分强大

#### lazygit

```shell
yay -S lazygit
```

终端下的`git`工具

#### zsh

```shell
sudo pacman -S zsh
```

配合oh-my-zsh让命令写起来很爽，zsh插件使用的zinit管理

oh-my-zsh项目地址：https://github.com/ohmyzsh/ohmyzsh

拉取GitHub的oh-my-zsh会很慢，可以使用Gitee的oh-my-zsh：https://gitee.com/mirrors/oh-my-zsh，下载`tools`中的`install.sh`脚本，修改以下`Default settings`内容

```diff
# Default settings
ZSH=${ZSH:-~/.oh-my-zsh}
-REPO=${REPO:-ohmyzsh/ohmyzsh}
+REPO=${REPO:-mirrors/oh-my-zsh}
-REMOTE=${REMOTE:-https://github.com/${REPO}.git}
+REMOTE=${REMOTE:-https://gitee.com/${REPO}.git}
BRANCH=${BRANCH:-master}
```

然后授权执行即可。

使用zinit进行插件管理，zinit项目地址：https://github.com/zdharma/zinit

#### rofi

```shell
sudo pacman -S rofi
```

配合polybar-themes更好看

polybar-themes项目地址：https://github.com/adi1090x/polybar-themes

#### alsa-utils

```shell
pacman -S alsa-utils
```

终端音频控制软件，使用`alsamixer`命令调出

#### st

十分小巧但功能强大的终端模拟器，这个终端需要自己拉取源码编译，原始的版本很丑，但是可以打补丁，在GitHub上也有打过补丁的仓库

项目地址：https://st.suckless.org/

#### Alacritty

```shell
sudo pacman -S alacritty
```

rust写的用GPU渲染的终端模拟器，st和alacritty我都在使用

#### ranger

```shell
sudo pacman -S ranger
```

终端下的文件管理器，在文件夹间跳转太方便了，爱不释手

#### wget

```shell
sudo pacman -S wget
```

下载文件使用

#### flameshot

```shell
sudo pacman -S flameshot
```

截图软件，需要用命令启动

```shell
flameshot gui
```

#### feh

```shell
sudo pacman -S feh
```

设置桌面壁纸的软件

```shell
feh --bg-scale 壁纸路径
```



#### fcitx5

```shell
sudo pacman -S fcitx5-qt fcitx5-gtk fcitx5-configtool
```

#### neofetch

```shell
sudo pacman -S neofetch
```

在终端下使用`neofetch`命令查看整体系统信息

#### htop

```shell
sudo pacman -S htop
```

终端下的进程管理器，用`htop`命令调出

#### fzf

```shell
sudo pacman -S fzf
```

终端下的文件查找工具

#### figlet

```shell
sudo pacman -S figlet
```

在终端下输出空心ASCII字符

#### toilet

```shell
sudo pacman -S toilet
```

终端下输出实心ASCII字符，可以附带颜色

#### pyenv

Linux上管理Python版本的工具，项目地址：https://github.com/pyenv/pyenv

通常用它管理Python版本，但是不用它创建虚拟环境

#### reflector

用来更新pacman镜像源

```shell
sudo pacman -S reflector
```

```shell
sudo reflector --verbose --country China --latest 15 rate --save /etc/pacman.d/mirrorlist
```

#### rsync

用于文件传输、复制、有断点续传的功能

```shell
sudo pacman -S rsync
```

#### tmux

终端复用工具

```shell
sudo pacman -S tmux
```

#### gpg

加密工具

```shell
sudo pacman -S gnupg
```

