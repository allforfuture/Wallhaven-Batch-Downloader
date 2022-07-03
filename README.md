

# 批量下载wallhaven壁纸


推荐另一个项目，无需安装软件，在浏览器页面实现每张图片的快速下载：https://github.com/lthero-big/WallHaven-One-Click-Download



## 功能

* 支持按**搜索结果或标签**下载：需要您提前在wallhaven页面搜索或选择标签，并复制搜索结果的链接到程序里面，并点击“**开始从此页面下载**”
* 支持按**条件筛选**下载：无需在浏览器操作，只要在程序**下半部分**，选择好条件，再点击“**开始按条件下载**”




## 特点

* 多线程下载，速度较快


## 使用说明

**先选择文件夹 ！**

- 可以**复制一个网址**，从指定网址（可以是搜索结果页面，或标签页面）下载几页的内容

如复制网址：https://wallhaven.cc/hot 并选择下载**3**页 ，点“**开始从此页面下载**”即可

- 可以**不复制网址**，选择好要下载的内容，点“**开始按条件**”即可




## 版本说明

* 程序分为**有界面**、**无界面**、**上传到阿里云** 三个版本



### 有界面

* 有界面的版本使用PYQT实现，名称为 index-withUI.py
* 无需安装环境，win10、win11下可用
* 打包程序可直接运行：蓝奏:https://wwa.lanzoui.com/b00uisw1a 密码:e5f2



### 无界面

* 无界面的版本纯python代码，名称为 index-withoutUI.py
* 需要运行代码后，输入命令再下载



### 上传版本

* 上传到阿里云版本，名称为 upload version
* 功能：直接将壁纸下载到**阿里云的OSS**中，满足一些特定场景下需求
* 需要手动修改代码中“**阿里云账号与密码**”以及**路径**
