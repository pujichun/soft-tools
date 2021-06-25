## 浏览器

[Chrome](https://www.google.cn/chrome/)

## Coding

#### 编译器和解释器

[Python](https://python.org/)

华为镜像地址：https://repo.huaweicloud.com/python/

- 配置环境变量

  ```bash
  python -V
  ```

- 设置镜像地址

  ```bash
  pip config set global.index-url https://repo.huaweicloud.com/repository/pypi/simple
  ```

[node](https://nodejs.org/)

- 配置环境变量

  ```bash
  node --version
  ```

- 设置全局模块的存放路径、cache的路径

  ```bash
  npm config set prefix "D:\soft\nodejs\node_global"
  npm config set cache "D:\soft\nodejs\node_cache"
  ```

- 拉取cnpm

  ```bash
  npm install -g cnpm --registry=https://registry.npm.taobao.org
  ```

[Go](https://studygolang.com/dl)

- 设置GOROOT、GOPATH

- 设置GOPROXY

  ```bash
  https://goproxy.io,direct
  ```

- 查看环境配置

  ```bash
  go env
  ```

[Gcc](https://sourceforge.net/projects/mingw-w64/files/)

- 设置环境变量

  ```bash
  gcc -v
  ```

[JDK8](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.htm)

华为开源镜像站：https://repo.huaweicloud.com/openjdk/

#### 数据库

[MySQL](https://pujichun.gitee.io/2020/03/14/MySQL%E5%AE%89%E8%A3%85%E9%85%8D%E7%BD%AE/)

[MongoDB](https://pujichun.gitee.io/2020/03/14/MongoDB%E7%9A%84%E5%AE%89%E8%A3%85%E4%BB%A5%E5%8F%8A%E9%85%8D%E7%BD%AE/)

#### mycli

```bash
pip install mycli
```

#### 编辑器和IDE

[vscode](https://code.visualstudio.com/)

- 同步配置
- 使用setting sync插件
- 修改配置文件

[typora](https://www.typora.io/)

- 打开设置中的markdown扩展语法中的内联公式、数学公式自动添加序号

[jetbrains-toolbox-app](https://www.jetbrains.com/toolbox-app/)

- 设置存储位置和删除旧版本



#### 版本控制

[Git](https://git-scm.com/)

## 其他工具

#### ftp

[filezilla](https://www.filezilla.cn/)

#### 终端&ssh

Windows terminal（微软应用商店下载）

[mobaxterm](https://mobaxterm.mobatek.net/)

#### 数据库可视化

[HeidiSQL](https://www.heidisql.com/)

[compass](https://www.mongodb.com/try/download/compass)

[AnotherRedisDesktopManager](https://github.com/qishibo/AnotherRedisDesktopManager)

#### 流程图

[drawio](https://github.com/jgraph/drawio-desktop)

![](https://gitee.com/pujichun/BlogImage/raw/master/img/QQ%E6%88%AA%E5%9B%BE20210625171004.png)

#### GIF录制

[ScreenToGif](https://github.com/NickeManarin/ScreenToGif)

![](https://gitee.com/pujichun/BlogImage/raw/master/img/20210625171225.png)

能对最后录制的每一帧画面进行编辑

#### 抓包

[Charles](https://www.charlesproxy.com/)

[wireshark](https://www.wireshark.org/)

#### 图床

[PicGo](https://github.com/Molunerfinn/PicGo)

![](https://gitee.com/pujichun/BlogImage/raw/master/img/20210625170350.png)

#### 文件查找

[everything](https://www.voidtools.com/zh-cn/)

![](https://gitee.com/pujichun/BlogImage/raw/master/img/20210625170503.png)

速度极快

#### 不可描述软件

clash

#### 字体

[nerd font](https://github.com/ryanoasis/nerd-fonts)

#### 视频播放器

[Potplayer](https://potplayer.daum.net/?lang=zh_CN)

#### Qucklook

Windows应用商店下载，文件快速预览

![](https://gitee.com/pujichun/BlogImage/raw/master/img/20210625170158.png)

像csv数据，code，图片都可以预览很方便

#### PowerToys

类似于mac上的聚焦搜索，[PowerToys](https://github.com/microsoft/PowerToys)

![](https://gitee.com/pujichun/BlogImage/raw/master/img/image-20210625170328183.png)

#### scoop

Windows下的一个包管理器

![](https://gitee.com/pujichun/BlogImage/raw/master/img/20210625172741.png)

- 设置scoop安装位置

  管理员权限打开powershell(或者Windows Terminal)

  ```shell
  $env:SCOOP='D:\soft\scoop'
  ```

- 配置包安装的位置

  ```shell
  $env:SCOOP_GLOBAL='F:\GlobalScoopApps'
  ```

- 安装

  ```shell
  Invoke-Expression (New-Object System.Net.WebClient).DownloadString('https://get.scoop.sh')
  ```

#### chocolatey

[chocolatey](https://chocolatey.org/)是Windows下的另一个包管理器，和scoop搭配使用

![](https://gitee.com/pujichun/BlogImage/raw/master/img/20210625173918.png)

- 安装

  ```shell
  Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
  ```

- 更改安装位置

  - 安装位置暂时不知道如何直接更改，可以安装以后将目录剪切到想要安装的位置
  - 修改环境变量中的值

- 更改包安装的位置

  - 修改环境变量

#### oh-my-posh

[oh-my-posh](https://github.com/JanDeDobbeleer/oh-my-posh)是一个Windows下的终端美化工具，搭配Windows Terminal使用，毕竟代码不会天天写但是终端天天用

因为安装过程稀里糊涂，所以~~弄明白后更新~~

主题可以参照[官方文档](https://ohmyposh.dev/docs/themes)

![](https://gitee.com/pujichun/BlogImage/raw/master/img/20210625170658.png)