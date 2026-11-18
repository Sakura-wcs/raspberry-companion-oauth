---
title: Raspberry Companion Backup
---

# Raspberry Companion Backup

Raspberry Companion Backup 是一款自托管备份工具，用于将树莓派上的数字伙伴配置和状态保存为可恢复的快照。用户可选择通过 rclone 将加密副本保存到自己授权的 Google Drive。

## 工作方式

1. 在用户管理的设备上生成并校验本地备份。
2. 启用 Google Drive 后，工具在本地生成密码保护的 AES-256 加密 7z 压缩包，验证后再上传。
3. 用户可从 Google Drive 下载压缩包，使用自己的备份密码解密。请单独保存密码，并定期验证备份可恢复。

本网站提供应用说明和公开政策，不是备份上传、账号登录或文件托管服务。

## 用户文档

- [隐私权政策](./privacy.html)
- [服务条款](./terms.html)
- [问题反馈](https://github.com/Sakura-wcs/raspberry-companion-oauth/issues)

问题反馈区公开可见，请不要提交备份文件、访问令牌、密钥或密码。
