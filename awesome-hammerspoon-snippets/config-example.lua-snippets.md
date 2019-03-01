# config-example.lua

[TOC]

## 选择要加载的Spoons

```lua
hspoon_list = {
    "AClock",
    "BingDaily",
    -- "Calendar",
    "CircleClock",
    "ClipShow",
    "CountDown",
    "FnMate",
    "HCalendar",
    "HSaria2",
    "HSearch",
    -- "KSheet",
    "SpeedMenu",
    -- "TimeFlow",
    -- "UnsplashZ",
    "WinWin",
}
```

## appM 键位绑定 appM environment keybindings.

Bundle `id` is prefered, but application `name` will be ok.

```lua
hsapp_list = {
    {key = 'a', name = 'Atom'},
    {key = 'c', id = 'com.google.Chrome'},
    {key = 'd', name = 'ShadowsocksX'},
    {key = 'e', name = 'Emacs'},
    {key = 'f', name = 'Finder'},
    {key = 'i', name = 'iTerm'},
    {key = 'k', name = 'KeyCastr'},
    {key = 'l', name = 'Sublime Text'},
    {key = 'm', name = 'MacVim'},
    {key = 'o', name = 'LibreOffice'},
    {key = 'p', name = 'mpv'},
    {key = 'r', name = 'VimR'},
    {key = 's', name = 'Safari'},
    {key = 't', name = 'Terminal'},
    {key = 'v', id = 'com.apple.ActivityMonitor'},
    {key = 'w', name = 'Mweb'},
    {key = 'y', id = 'com.apple.systempreferences'},
}
```


## 模块程序键位绑定

Modal supervisor keybinding, which can be used to temporarily disable ALL modal environments.

```lua
hsupervisor_keys = {{"cmd", "shift", "ctrl"}, "Q"}
```
## 重新加载Hammerspoon配置
Reload Hammerspoon configuration

```lua
hsreload_keys = {{"cmd", "shift", "ctrl"}, "R"}
```
## 浏览帮助信息
Toggle help panel of this configuration.

```lua
hshelp_keys = {{"alt", "shift"}, "/"}
```

## aria2 RPC host address
hsaria2_host = "http://localhost:6800/jsonrpc"

```lua
-- aria2 RPC host secret
hsaria2_secret = "token"
```

## 以下键位绑定可以disabled
Those keybindings below could be disabled by setting to {"", ""} or {{}, ""}


## 窗口提示
-- Window hints keybinding: Focuse to any window you want

```lua
hswhints_keys = {"alt", "tab"}
```
## 登录appM
-- appM environment keybinding: Application Launcher

```lua
hsappM_keys = {"alt", "A"}
```

## 显示系统剪贴板
clipshowM environment keybinding: System clipboard reader

```lua
hsclipsM_keys = {"alt", "C"}
```

## 查看aria2
Toggle the display of aria2 frontend

```lua
hsaria2_keys = {"alt", "D"}
```


## 显示Hammerspoon搜索
Launch Hammerspoon Search

```lua
hsearch_keys = {"alt", "G"}
```


## 读取Hammerspoon和Spoons的API手册
Read Hammerspoon and Spoons API manual in default browser

```lua
hsman_keys = {"alt", "H"}
```

## countdownM 键位绑定
countdownM environment keybinding: Visual countdown

```lua
hscountdM_keys = {"alt", "I"}
```


## 锁屏 Lock computer's screen

```lua
hslock_keys = {"alt", "L"}
```



## resizeM 键位绑定 environment keybinding: Windows manipulation

```lua
hsresizeM_keys = {"alt", "R"}
```


## cheatsheetM 键位绑定environment keybinding: Cheatsheet copycat
hscheats_keys = {"alt", "S"}

## Show digital clock above all windows

```lua
hsaclock_keys = {"alt", "T"}
```



## 在Chrome或Safari中打开网页
Type the URL and title of the frontmost web page open in Google Chrome or Safari.
hstype_keys = {"alt", "V"}

## 浏览Hammerspoon控制台
Toggle Hammerspoon console

```lua
hsconsole_keys = {"alt", "Z"}
```

