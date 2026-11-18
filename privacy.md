---
title: Raspberry Companion Backup 隐私权政策
permalink: /privacy.html
---

# Raspberry Companion Backup 隐私权政策

更新于：2026 年 11 月 19 日

本政策说明 Raspberry Companion Backup 自托管工具及其公开说明网站如何处理信息。工具安装在用户管理的设备上；公开网站由 GitHub Pages 托管。

## 本地备份及 Google Drive 数据

工具读取本地配置的备份范围，生成数字伙伴配置和运行状态的快照。启用 Google Drive 后，工具通过 rclone 使用 Google OAuth 的 `drive.file` 权限，访问它创建或获准访问的文件和文件夹。它仅将该访问用于定位备份目录、上传、列出、验证或下载备份，以便恢复。

工具在设备上加密压缩包后才上传。备份包的名称、大小和上传时间等外部元数据仍可由 Google Drive 处理。Google OAuth 凭据和压缩包密码保存在用户设备的受限文件中，不包含在备份包内，也不会提交给本说明网站。

Google API 获取的数据仅用于向用户提供上述备份功能，不用于广告，不出售，也不会发送到项目维护者的服务器。应用对 Google API 数据的使用遵守 [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy)，包括其 Limited Use 要求。Google Drive 本身的数据处理适用 [Google 隐私权政策](https://policies.google.com/privacy)。

## 保留、删除和撤销授权

本地和云端备份由用户管理。用户可在设备上清理本地备份，也可在 Google Drive 中删除云端副本；需要永久删除时，请同时处理 Drive 回收站。用户可在 [Google 账号的第三方连接设置](https://myaccount.google.com/connections) 撤销访问权限，并在设备上删除本地授权配置。撤销访问权限不自动删除已上传的备份。

## 网站访问和联系

本网站没有账号注册、备份上传表单或项目方运营的分析跟踪工具。GitHub 作为托管服务商可能按其 [隐私声明](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement) 处理访问所需的技术信息。

如对本政策有疑问，可通过 [GitHub 问题反馈](https://github.com/Sakura-wcs/raspberry-companion-oauth/issues) 联系维护者。反馈区公开可见，请勿发送个人敏感信息、备份或凭据。

[返回应用首页](./) · [服务条款](./terms.html)
