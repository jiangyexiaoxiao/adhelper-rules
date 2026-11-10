# 广告小帮手 云端规则库

这个仓库托管广告小帮手 App 的云端规则配置，无需登录，App 直接拉取 raw 文件。

## 文件说明

- `rules_manifest.json` - 规则库版本号，App 启动时检查是否需要更新内置规则
- `app_manifest.json` - App 最新版本号和下载地址，设置页"检查更新"用

## 如何更新

1. 修改对应 JSON 文件的 version 字段
2. commit + push 到 main 分支
3. App 下次检查时自动发现新版本
