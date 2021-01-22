### 简介

官网下载：https://rime.im/download

官方文档：https://github.com/rime/home/wiki



### 安装

RIME 是一款开源、跨平台、且简洁流畅的输入法引擎， 不同平台有着不同代号：

- **Windows：** 小狼毫( [Weasel](https://github.com/rime/weasel))【[下载](https://bintray.com/rime/weasel/release)】



- **MacOS：** 鼠须管([Squirrel](https://github.com/rime/squirrel))【[下载](https://bintray.com/rime/squirrel/release)】

- **Linux：** 中州韵                  

### 用法
 1. 安装Rime输入法,并注销或重启
 2. 下载仓库配置文件复制到本地配置文件夹
 
   安装完毕需要重新部署`，或者注销用户重新登录

### 文件位置

```
~/.config/ibus/rime  (Linux)
~/Library/Rime  (Mac OS)
%APPDATA%\Rime  (Windows)
```

### 文件说明

```
default.custom.yaml: 自定义的全局配置
输入方案名.schema.yaml：输入方案的默认配置文件
输入方案名.custom.yaml: 自定义方案配置文件
输入方案名.dict.yaml: 输入词典源文件
symbols.custom.yaml: 自定义符号的设置
installation.yaml: 安装时自动创建的配置文件
```

### 快捷键

```
Ctrl + ` or F4  # 打开设置菜单
Ctrl + .        # 切换标点符号
Ctrl + Delete   # 删除用户词条
```

