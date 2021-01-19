![platform](https://img.shields.io/badge/platform-macos-lightgrey.svg)  ![release](https://img.shields.io/badge/release-v2.8.2-brightgreen.svg)  ![support](https://img.shields.io/badge/support-wechat%202.6.0-blue.svg) 
## 声明
- `BrianWeChatExtension`是基于[WeChatExtension](https://github.com/MustangYM/WeChatExtension-ForMac)项目的分支。
- 适用于Mac版的WeChat拓展功能。
- 到目前为止，并未发现因使用本插件会导致封号。

## 最新支持版本
- [下载最新版微信](https://dldir1.qq.com/weixin/mac/WeChatMac_Beta.dmg)。
- 皮肤最低支持macOS 10.14。

## 安装
### 安装方式一：普通安装(clone最新版本并安装)
```
sudo rm -r -f WeChatExtension-ForMac && git clone --depth=1 https://github.com/XXXBRIAN/WeChatExtension-ForMac && cd WeChatExtension-ForMac/WeChatExtension/Rely && ./Install.sh
```

### 安装方式二：手动安装

- 1.确保你的Mac上已经安装了微信App。

- 2.下载本项目到你的电脑里， 并双击打开。
<p align="center">
<img src="https://gitee.com/MustangYM/we-chat-extension-source/raw/master/Pictures/WX20190619-112238.png" width="800px"/>
</p>

- 3.依次打开文件夹
<p align="center">
<img src="https://gitee.com/MustangYM/we-chat-extension-source/raw/master/Pictures/WX20190619-113413%402x.png" width="800px"/>
</p>

- 4.打开你电脑中的终端工具
<p align="center">
<img src="https://gitee.com/MustangYM/we-chat-extension-source/raw/master/Pictures/WX20190619-113911%402x.png" width="800px"/>
</p>
 
- 5.在Rely/Install.sh执行这个安装脚本
<p align="center">
<img src="https://gitee.com/MustangYM/we-chat-extension-source/raw/master/Pictures/QQ20190425-155120%402x.png" width="800px"/>
</p>

- 6.重启微信，安装完成。

## 卸载
### 卸载方式一：自动卸载（推荐）
```
bash <(curl -sL https://git.io/JttIN)
```
### 卸载方式二：手动卸载
  -  将Uninstall.sh拖到终端工具中，回车执行即可。
<p align="center">
<img src="https://gitee.com/MustangYM/we-chat-extension-source/raw/master/Pictures/WX20190625-102808%402x.png" width="800px"/>
</p>


## License

MIT license. 
