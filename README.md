[English](README_en.md)

[中文](README.md)

# 高级离线二维码工具

一个完全离线的二维码生成与扫描工具，使用本地库，无需互联网连接。注意：仅支持Chrome浏览器。

## 功能特点

- 从文本、URL或任何内容生成二维码
- 自定义二维码尺寸、前景色和背景色
- 将生成的二维码下载为PNG图片
- 使用摄像头扫描二维码（需要摄像头权限）
- 一键复制扫描内容
- 直接打开扫描到的URL链接
- 流畅的动画效果和响应式设计

## 使用方法

1. 将此仓库克隆到本地
2. 在Chrome浏览器中打开`offline-qrcode-tool.html`文件
3. 使用"生成二维码"面板创建二维码
4. 使用"扫描二维码"面板扫描二维码（首次使用时请允许摄像头访问）

## 技术细节

- 二维码生成使用 [qrcode.min.js](https://davidshimjs.github.io/qrcodejs/)
- 二维码扫描使用 [jsQR](https://github.com/cozmo/jsQR)
- 纯前端实现，无需后端支持
- 下载后可离线使用

## 截图

![image](https://github.com/user-attachments/assets/6229e0d6-8fcc-4df6-af41-003f90b76e6b)


## 许可证

MIT许可证
