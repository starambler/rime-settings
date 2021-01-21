### 简介

官网下载：https://rime.im/download

官方文档：https://github.com/rime/home/wiki



### 安装

RIME 是一款开源、跨平台、且简洁流畅的输入法引擎， 不同平台有着不同代号：

- **Windows：** 小狼毫( [Weasel](https://github.com/rime/weasel))【[下载](https://bintray.com/rime/weasel/release)】



- **MacOS：** 鼠须管([Squirrel](https://github.com/rime/squirrel))【[下载](https://bintray.com/rime/squirrel/release)】

```bash
# [brew](https://brew.sh/index_zh-cn)

brew cask install squirrel
```


- **Linux：** 中州韵
          
``` bash
# Ubuntu
sudo apt-get install ibus-rime

# Fedora
sudo dnf install ibus-rime

# [更多发行版...](https://github.com/rime/home/wiki/RimeWithIBus)
```
                    

### 重启输入法
安装完毕需要重启输入法`ibus restart`，或者注销用户重新登录




### 使用配置

本配置适用于Linux（朙月拼音·简化字）配置

```bash
# 下载配置文件
git clone https://github.com/jayknoxqu/ibus-rime.git

# 复制配置文件
cp -r ibus-rime/* ~/.config/ibus/rime

# 部署配置文件
ibus-daemon -drx
```



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



### 输入方案

```
朙月拼音	luna_pinyin
朙月拼音·简化字	luna_pinyin_simp
朙月拼音·臺灣正體	luna_pinyin_tw
朙月拼音·語句流  luna_pinyin_fluency
自然碼雙拼	 double_pinyin
智能ABC雙拼  double_pinyin_abc
小鶴雙拼  double_pinyin_flypy
MSPY雙拼  double_pinyin_mspy
```



### 快捷键

```
Ctrl + ` or F4  # 打开设置菜单
Ctrl + .        # 切换标点符号
Ctrl + Delete   # 删除用户词条
```

