# 空白标签页 浏览器插件
目的：解决 Chrome 使用商店的第三方空白标签扩展时，“仅在新标签页显示书签”功能不可用问题

扩展仅 802 字节大小

本扩展的预备安装操作可能会带来风险，如果你接受不了，请关闭此页面右转
> #### 步骤
# 一、
> 打开 chrome://flags/#extensions-on-chrome-urls

> 设置 Extensions on chrome:// URLs 为 Enabled

此选项为 允许第三方扩展访问 Chrome:// 链接。需第三方扩展自身请求权限才允许访问

（猜想：商店里的扩展若加上该权限可能不被允许发布）

# 二、
> 打开 chrome://extensions

> 点击右上角 开发者模式，设置为启用状态

> 下载本项目文件并解压，记住文件夹位置

> 点击左上角 加载已解压的扩展程序，选择文件夹位置

# 完成

<br>

<br>

# License

Copyright (C) 2022 HolyshitOvO

Licensed under the GPLv3: http://www.gnu.org/licenses/gpl-3.0.html

Please do not contact me except on this Github project issues.

GPL-3.0 license


