# awesome-hammerspoon

> awesome-hammerspoon 是我的 [Hammerspoon](http://www.hammerspoon.org/) 的配置文件，也是 [ashfinal的awesome-hammerspoon](https://github.com/ashfinal/awesome-hammerspoon)的一个分支.


[TOC]


## 安装与更新

### 安装

1. 安装 [Hammerspoon](http://www.hammerspoon.org/).

2. `git clone https://github.com/suliveevil/awesome-hammerspoon.git ~/.hammerspoon`

3. Reload the configutation.

### 更新

`cd ~/.hammerspoon && git pull`

## 使用（附截图展示）

按下 <kbd>opt</kbd>, 与 <kbd>A</kbd> 或者 <kbd>C</kbd> 或者 <kbd>R</kbd>.
如果需要帮助, 按下 <kbd>tab</kbd> 浏览 the keybindings cheatsheet.

Press <kbd>opt</kbd> + <kbd>?</kbd> to toggle the help panel, which will show all <kbd>opt</kbd> related keybindings.


这些截图描述了 awesome-hammerspoon 能做什么. 
了解更多 [built-in Spoons](https://github.com/ashfinal/awesome-hammerspoon/wiki/The-built-in-Spoons).

### 桌面插件

<details>
<summary>More details</summary>

![widgets](https://github.com/ashfinal/bindata/raw/master/screenshots/awesome-hammerspoon-deskwidgets.png)

</details>

### 窗口管理 
<kbd>⌥</kbd> + <kbd>R</kbd>

<details>
<summary>More details</summary>

![winresize](https://github.com/ashfinal/bindata/raw/master/screenshots/awesome-hammerspoon-winresize.gif)

</details>

### 快速搜索
<kbd>⌥</kbd> + <kbd>G</kbd>

<details>
<summary>More details</summary>

![hsearch](https://github.com/ashfinal/bindata/raw/master/screenshots/awesome-hammerspoon-hsearch.gif)

</details>

### aria前端
<kbd>⌥</kbd> + <kbd>D</kbd>

<details>
<summary>More details</summary>


使用之前，你需要 [run aria2 with RPC enabled](https://github.com/ashfinal/awesome-hammerspoon/wiki/Run-aria2-with-rpc-enabled).

```bash
aria2c --enable-rpc
```

在 `~/.hammerspoon/private/config.lua` 里配置 aria2 host 和 token.

```lua
hsaria2_host = "http://localhost:6800/jsonrpc" -- default host
hsaria2_secret = "token" -- YOUR OWN SECRET
```

![hsearch](https://github.com/ashfinal/bindata/raw/master/screenshots/awesome-hammerspoon-aria2.png)

</details>

## 个性化定制 Customization

<details>

<summary>More details</summary>

```shell
cp ~/.hammerspoon/config-example.lua ~/.hammerspoon/private/config.lua
```

修改配置文件 `~/.hammerspoon/private/config.lua`:

### 添加/删除 Spoons.

  在 `hspoon_list` 里决定加载哪些 Spoons (Hammerspoon 模块). 这里有 15 个 [内置 Spoons](https://github.com/ashfinal/awesome-hammerspoon/wiki/The-built-in-Spoons).

  *这里有更多的Spoons [official spoon repository](http://www.hammerspoon.org/Spoons/) (使用之前需要配置一下).*

### 自定义键盘绑定 keybindings

  Please read `~/.hammerspoon/private/config.lua`for more details.

Finally press `cmd + ctrl + shift + r` to reload the configuration.

</details>

## Hammerspoon可以代替的软件
### 窗口管理
<details>
<summary>More details</summary>
如果你更喜欢键盘控制窗口，那么Hammerspoon是你的菜，你还能免去安装magnet（Mac App Store，收费）、Spectacle（免费）等键盘调整窗口布局的app。
如果你更喜欢触控板、鼠标调整窗口，你也可以使用Moom等软件。
#### Magnet
#### Spectacle
#### Moom（Mac App Store，收费）
</details>

### 键盘绑定
<details>
<summary>More details</summary>
#### Karabiner-Elements（部分功能可代替）
#### Keyboard Maestro（收费）（部分功能可代替）
</details>

### 搜索
<details>
<summary>More details</summary>
#### Alfred（收费）
</details>

## 贡献

<details>
<summary>More details</summary>

### 改进现有 Spoons

  一个 "Spoon" 就是一个词典, 右击它 -> "显示包内容".

  有问题请随时提交 issue 或 PR.

### 创建新 Spoons

  一些可能有用的资源:

  [Learn Lua in Y minutes](http://learnxinyminutes.com/docs/lua/)

  [Getting Started with Hammerspoon](http://www.hammerspoon.org/go/)

  [Hammerspoon API Docs](http://www.hammerspoon.org/docs/index.html)

  [hammerspoon/SPOONS.md at master · Hammerspoon/hammerspoon](https://github.com/Hammerspoon/hammerspoon/blob/master/SPOONS.md)

</details>

## 致谢

[ashfinal awesome-hammerspoon](https://github.com/ashfinal/awesome-hammerspoon)
[zzamboni oh-my-hammerspoon](https://github.com/zzamboni/oh-my-hammerspoon)
[scottcs dot_hammerspoon](https://github.com/scottcs/dot_hammerspoon)
[dharmapoudel hammerspoon-config](https://github.com/dharmapoudel/hammerspoon-config)

[http://tracesof.net/uebersicht/](http://tracesof.net/uebersicht/)

