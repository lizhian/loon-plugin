# loon-plugin

用于定位哔哩哔哩弹幕加载问题的 Loon 插件诊断副本，尚未验证修复效果。

## 手机安装

在 Loon 的插件页面添加以下 URL：

```text
https://raw.githubusercontent.com/lizhian/loon-plugin/main/Bilibili_remove_ads_DmView_diagnostic.lpx
```

测试时关闭原版「哔哩哔哩去广告」，只启用诊断版；彻底退出哔哩哔哩后重开同一个视频。

## 来源与修改

- 原插件：https://kelee.one/Tool/Loon/Lpx/Bilibili_remove_ads.lpx
- 原作者：kokoryh（https://github.com/kokoryh）
- 原插件日期：2026-10-02
- 修改：从 ProtoBuf 响应脚本的匹配范围中移除 `DmView` 接口，并修改插件名称以便区分。
- 其余规则及外部脚本 URL 保留原样；外部脚本仍从原站加载，不在本仓库托管。

适用于 iOS / iPadOS。原作者信息保留于插件文件中。
