# 老君音乐 TWA Android APK

把 music-manager Web UI 打包成独立 Android App。

## 配置
- **包名**: `com.myrte.musicmanager`
- **名称**: 老君音乐
- **入口**: https://mx.7lzh.com:4343 (NPS 转发到本地 5098)
- **主题色**: #1a1a2e (深紫)

## 编译
GitHub Actions 自动构建，每次 push 或手动触发。

## 安装
1. 编译完 → Artifacts → 下载 `laojun-music-apk`
2. 解压 → `app/build/outputs/apk/release/app-release.apk`
3. 传到 Android 手机 → 安装

## 更新
改 `app/build.gradle` 里的 `twaManifest` 配置后 push。
