<h1 align="center">XChat</h1>
<h3 align="center">XChat 是一款集文件共享、聊天与 Markdown 编辑于一体的内网协作工具</h3>
<p align="center">
  <img src="https://img.shields.io/badge/Version-V1.0.0-green?style=flat">
  <img src="https://img.shields.io/github/stars/chasingboy/XChat?style=flat&labelColor=rgb(41%2C52%2C52)&color=green">
  <img src="https://img.shields.io/github/issues/chasingboy/XChat">
  <img src="https://img.shields.io/github/downloads/chasingboy/XChat/total?style=flat&labelColor=rgb(41%2C52%2C52)&color=green">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=chasingboy.XChat&left_color=green&right_color=#66ccff">
</p>

### 前言
> 有时在内网扫描渗透时，不方便与团队成员共享文件和交流信息，所以在AI的辅助下快速搞出了一个 XChat。

XChat 是一款面向内网环境的轻量级协作工具，集 文件共享、即时聊天、Markdown 文档编写 于一体，旨在为团队提供一个简单、高效、安全的本地协作平台。

### 功能
#### 📁 内网文件共享
✅ 支持图片预览功能</br>
✅ 支持文件上传｜下载｜管理</br>
✅ 支持文件夹创建｜重命名｜删除等操作</br>
✅ 所有文件存储于本地服务器，数据可控、安全可靠</br>

#### 💬 即时聊天
✅ 提供轻量级聊天功能，满足团队基本沟通需求</br>
✅ 无需复杂注册流程，快速进入群聊</br>

#### 📝 Markdown 文档编写
✅ 内置 Markdown 编辑能力</br>
✅ 支持团队内部文档记录｜修改等操作</br>

### 基本使用
**默认密钥 secret｜默认端口 8888**
```
kali$ ./XChat -h
Usage of ./XChat:
  -key string
    	Authentication key (default "secret")
  -port string
    	Server port (default "8888")
```

**强烈建议自定义 key**
```bash
kali$ ./XChat -key "admin666" -port 9999
```
### 功能预览
<img width="1316" alt="image" src="https://github.com/chasingboy/XChat/blob/main/assets/file.png">
<img width="1316" alt="image" src="https://github.com/chasingboy/XChat/blob/main/assets/markdown.png">
<img width="1316" alt="image" src="https://github.com/chasingboy/XChat/blob/main/assets/chat.png">

### 更新记录
[+] 2026-04-15【发布】XChat V1.0.0
