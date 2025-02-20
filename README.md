<p align="center">
<img alt="SiYuan" src="https://b3log.org/images/brand/siyuan-128.png">
<br>
<em>The next generation PKM system, your digital garden</em>
<br><br>
<a title="Releases" target="_blank" href="https://github.com/siyuan-note/siyuan/releases"><img src="https://img.shields.io/github/release/siyuan-note/siyuan.svg?style=flat-square&color=FF9900"></a>
<a title="Downloads" target="_blank" href="https://github.com/siyuan-note/siyuan/releases"><img src="https://img.shields.io/github/downloads/siyuan-note/siyuan/total.svg?style=flat-square&color=blueviolet"></a>
<a title="Docker Pulls" target="_blank" href="https://hub.docker.com/r/b3log/siyuan"><img src="https://img.shields.io/docker/pulls/b3log/siyuan.svg?style=flat-square&color=99CCFF"></a>
<a title="QQ Group" target="_blank" href="https://jq.qq.com/?_wv=1027&k=OmaV22we"><img src="https://img.shields.io/static/v1?label=Q%20Group&style=flat-square&message=155585856&color=D28EFF"></a>
<a title="Discord" target="_blank" href="https://discord.gg/bzfCBwMzdP"><img src="https://img.shields.io/discord/808152298789666826?label=discord&style=flat-square&color=orange"></a>
<a title="Hits" target="_blank" href="https://github.com/siyuan-note/siyuan"><img src="https://hits.b3log.org/siyuan-note/siyuan.svg"></a>
</p>

<p align="center">
<a href="https://github.com/siyuan-note/siyuan/blob/master/README_zh_CN.md">中文</a>
</p>

## 💡 Introduction

SiYuan is a local-first personal knowledge management system, support fine-grained block-level reference and Markdown
WYSIWYG.

![feature0.png](https://cdn.jsdelivr.net/gh/siyuan-note/siyuan@aa842a59b28a873dcc999fb63eaeafb4158c02d3/screenshots/feature0.png)

![feature1-1.png](https://cdn.jsdelivr.net/gh/siyuan-note/siyuan@aa842a59b28a873dcc999fb63eaeafb4158c02d3/screenshots/feature1-1.png)

## ✨ Features

### Free

All local features are free.

* Content block
  * Block-level reference and two-way links
  * Document relationship diagram, global relationship diagram
  * Custom attributes
  * SQL query embed
  * Protocol `siyuan://`
* Editor
  * Block-style
  * Markdown WYSIWYG
  * List outline
  * Block zoom-in
  * Block horizontal layout
  * Million-word large document editing
  * Mathematical formulas, charts, flowcharts, Gantt charts, timing charts, staffs, etc.
  * Web clipping
  * PDF Annotation link
* Export
  * Block ref and embed
  * Standard Markdown with assets
  * PDF, Word and HTML
  * Copy to WeChat MP, Zhihu and Yuque
* Community bazaar
  * Themes
  * Icons
  * Templates
  * Widgets
* Hierarchical tag
* Multi-tab, drag and drop to split screen
* Fulltext search
* Template snippet
* Keymap
* Themes and icons
* Android APP
* iOS APP
* Docker deployment
* [API](https://github.com/siyuan-note/siyuan/blob/master/API.md)

### Paid subscription

Cloud services require a paid subscription.

* VIP identity
* End-to-end encrypted data synchronization
* End-to-end encrypted data backup
* Cloud assets serving
* WeChat notification
* Cloud inbox (TBD)

## 🗺️ Roadmap

* [SiYuan development plan and progress](https://github.com/siyuan-note/siyuan/projects)
* [SiYuan Change logs](https://github.com/siyuan-note/siyuan/blob/master/CHANGE_LOGS.md)

## 🛠️ Download Setup

* [B3log](https://b3log.org/siyuan/en/download.html)
* [GitHub](https://github.com/siyuan-note/siyuan/releases)
* [Docker](https://hub.docker.com/r/b3log/siyuan)
* [App Store](https://apps.apple.com/us/app/siyuan/id1583226508)
* [Google Play](https://play.google.com/store/apps/details?id=org.b3log.siyuan)
* [Microsoft Store](https://www.microsoft.com/store/apps/9P7HPMXP73K4)

To get the latest Insider Preview, please send an email with your GitHub login name to 845765@qq.com, and we will invite you to join the SiYuan Insider Preview team, thanks.

## 🏘️ Community

* [Issues](https://github.com/siyuan-note/siyuan/issues)
* [Discord](https://discord.gg/bzfCBwMzdP)

## ❓ FAQ

### How does SiYuan store data?

The data is saved in the workspace folder (the default is in the user's home directory Documents/SiYuan, which can be modified in <kbd>Settings</kbd> - <kbd>About</kbd>), in the workspace data folder:

* `assets` are used to save all inserted asset files
* `templates` are used to save template snippets
* `widgets` are used to save widgets
* `emojis` are used to save emoji images
* The rest of the folders are the notebook folders created by the user, files with the suffix of `.sy` in the notebook folder are used to save the document data, and the data format is JSON

### Is SiYuan open source?

It is not completely open source at present, but some components and applications have been open sourced, and contributions are welcome.

* [User Guide](https://github.com/siyuan-note/user-guide-en_US)
* [Appearance](https://github.com/siyuan-note/appearance)
* [Data Parser](https://github.com/88250/protyle)
* [Editor Engine](https://github.com/88250/lute)
* [End-to-end encryption](https://github.com/siyuan-note/encryption)
* [Chrome Clipping Extension](https://github.com/siyuan-note/siyuan-chrome)
* [Android App](https://github.com/siyuan-note/siyuan-android)
* [iOS App](https://github.com/siyuan-note/siyuan-ios)

### Is there any note for deleting docs?

After deletion, the doc will not appear in the operating system's recycle bin, but will be deleted directly. When deleted, SiYuan will generate edit history.

### How can I just wrap and not start a new paragraph?

Please use <kbd>Shift+Enter</kbd>.

### How to move the heading and blocks below it?

Fold the heading and move it later.

### How to select multiple blocks across pages?

Click at the beginning, hold down <kbd>Shift</kbd> and click at the end after scrolling the page.

### How to adjust table rows and columns?

There is an operation entry in the block icon menu of the table block.

### How to use a third-party sync disk for data synchronization?

* Please only synchronize the `workspace/data/`, do not synchronize the entire workspace
* Please suspend third-party synchronization during the operation of SiYuan, otherwise data may be damaged. For details, please refer to [here](https://ld246.com/article/1626537583158)
* The data folder path on the Android is `internal storage device/Android/data/org.b3log.siyuan/files/siyuan/data/`, which is a private path of the application and cannot be read by other programs and can only be copied manually
* There is a conflict between third-party synchronization and SiYuan synchronization, please do not use at the same time

### What should I do if I forget the end-to-end password?

* Use the new workspace on the main device, manually copy the old workspace data folder to the new workspace
* New workspace can reset password
* The cloud uses the new cloud synchronization directory

If it is a mobile-end, uninstall and reinstall it (note: When the mobile-enduninstalls the application, the local workspace data will be deleted together).

### Do I need to pay for it?

Local functions are completely free to use, [Cloud services](https://b3log.org/siyuan/pricing.html) requires annual subscription, price is $72/year。

Users in non-Mainland China regions should not pay for subscriptions, because SiYuan Cloud Server cannot guarantee availability in non-Mainland China regions.

## 💌 Participate in contribution

At present, some components of SiYuan are open source, and contributions are welcome.

* [User Guide](https://github.com/siyuan-note/user-guide-en_US)
* [Appearance](https://github.com/siyuan-note/appearance)
* [Data Parser](https://github.com/88250/protyle)
* [Editor Engine](https://github.com/88250/lute)
* [End-to-end encryption](https://github.com/siyuan-note/encryption)
* [Chrome Clipping Extension](https://github.com/siyuan-note/siyuan-chrome)
* [Android](https://github.com/siyuan-note/siyuan-android)
* [iOS](https://github.com/siyuan-note/siyuan-ios)

## 🙏 Acknowledgement

SiYuan is made possible by the following open source projects.

* [https://github.com/golang/go](https://github.com/golang/go) `BSD-3-Clause License`
* [https://github.com/atotto/clipboard](https://github.com/atotto/clipboard) `BSD-3-Clause License`
* [https://github.com/vanng822/css](https://github.com/vanng822/css) `MIT License`
* [https://github.com/88250/flock](https://github.com/gofrs/flock) `BSD-3-Clause License`
* [https://github.com/88250/gulu](https://github.com/88250/gulu) `Mulan PSL v2`
* [https://github.com/88250/lute](https://github.com/88250/lute) `Mulan PSL v2`
* [https://github.com/olahol/melody](https://github.com/olahol/melody) `BSD-2-Clause License`
* [https://github.com/pdfcpu/pdfcpu](https://github.com/pdfcpu/pdfcpu) `Apache-2.0 License`
* [https://github.com/88250/protyle](https://github.com/88250/protyle) `Mulan PSL v2`
* [https://github.com/88250/vitess-sqlparser](https://github.com/blastrain/vitess-sqlparser) `Apache-2.0 License`
* [https://github.com/ConradIrwin/font](https://github.com/ConradIrwin/font) `MIT License`
* [https://github.com/Masterminds/sprig](https://github.com/Masterminds/sprig) `MIT License`
* [https://github.com/Xuanwo/go-locale](https://github.com/Xuanwo/go-locale) `Apache-2.0 License`
* [https://github.com/araddon/dateparse](https://github.com/araddon/dateparse) `MIT License`
* [https://github.com/common-nighthawk/go-figure](https://github.com/common-nighthawk/go-figure) `MIT License`
* [https://github.com/dgraph-io/ristretto](https://github.com/dgraph-io/ristretto) `Apache-2.0 License`
* [https://github.com/dustin/go-humanize](https://github.com/dustin/go-humanize) `MIT License`
* [https://github.com/emirpasic/gods](https://github.com/emirpasic/gods) `BSD-2-Clause License`
* [https://github.com/facette/natsort](https://github.com/facette/natsort) `BSD-3-Clause License`
* [https://github.com/flopp/go-findfont](https://github.com/flopp/go-findfont) `MIT License`
* [https://github.com/fsnotify/fsnotify](https://github.com/fsnotify/fsnotify) `BSD-3-Clause License`
* [https://github.com/gin-contrib/cors](https://github.com/gin-contrib/cors) `MIT License`
* [https://github.com/gin-contrib/gzip](https://github.com/gin-contrib/gzip) `MIT License`
* [https://github.com/gin-contrib/sessions](https://github.com/gin-contrib/sessions) `MIT License`
* [https://github.com/gin-gonic/gin](https://github.com/gin-gonic/gin) `MIT License`
* [https://github.com/imroc/req](https://github.com/imroc/req) `MIT License`
* [https://github.com/jackpal/gateway](https://github.com/jackpal/gateway) `BSD-3-Clause License`
* [https://github.com/jinzhu/copier](https://github.com/jinzhu/copier) `MIT License`
* [https://github.com/mattn/go-sqlite3](https://github.com/mattn/go-sqlite3) `MIT License`
* [https://github.com/mattn/go-zglob](https://github.com/mattn/go-zglob) `MIT License`
* [https://github.com/mitchellh/go-ps](https://github.com/mitchellh/go-ps) `MIT License`
* [https://github.com/mssola/user_agent](https://github.com/mssola/user_agent) `MIT License`
* [https://github.com/panjf2000/ants](https://github.com/panjf2000/ants) `MIT License`
* [https://github.com/siyuan-note/encryption](https://github.com/siyuan-note/encryption) `Mulan PSL v2`
* [https://github.com/xrash/smetrics](https://github.com/xrash/smetrics) `MIT License`
* [https://github.com/golang/image](https://github.com/golang/image) `BSD-3-Clause License`
* [https://github.com/golang/mobile](https://github.com/golang/mobile) `BSD-3-Clause License`
* [https://github.com/golang/text](https://github.com/golang/text) `BSD-3-Clause License`
* [https://github.com/microsoft/TypeScript](https://github.com/microsoft/TypeScript) `Apache-2.0 License`
* [https://github.com/electron/electron](https://github.com/electron/electron) `MIT License`
* [https://github.com/Vanessa219/vditor](https://github.com/Vanessa219/vditor) `MIT License`
* [https://github.com/visjs/vis-network](https://github.com/visjs/vis-network) `Apache-2.0 License`
* [https://github.com/mozilla/pdf.js](https://github.com/mozilla/pdf.js) `Apache-2.0 License`
* [https://github.com/blueimp/JavaScript-MD5](https://github.com/blueimp/JavaScript-MD5) `MIT License`
