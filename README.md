# MIUI IME Unlock

解锁 MIUI 全面屏优化限制

## 测试环境

LSPosed v1.2.2(API 93.0)

MUI 12.5

Android 11(R,API 30)

## 使用方法

Xposed API Version >= 93

在作用域勾选需要解除限制的输入法即可，小米定制版也要勾上

## 下载

[app/release/app-release.apk](app/release/app-release.apk)

或
<https://cdn.staticaly.com/gh/RC1844/MIUI_IME_Unlock/main/app/release/app-release.apk>

## 特别说明

1. 全面屏优化与百度输入法官方版存在兼容问题，这不属于本模块 BUG。
2. 因为本人在用的是 MIUI12.5，所以对于 MIUI12 适配并不完整，存在不可用的可能性。
3. 托盘按钮设置为小爱语音输入时，按钮失效不可用，目前未发现原因，但通过长按选择启动小爱似乎没有问题。
4. 不接受任何为特定输入法适配 xxx 的请求，这不现实不合理。

## 更新日志

v1.03

    加入对 MIUI 版本的检查
    修复 MIUI12 输入法切换菜单不全的问题
    现在仅对 MIUI12、MIUI12.5 生效

v1.02

    优化执行逻辑
    部分hook方法不会对定制版进行hook
    增加对底视图颜色的修改，颜色完全由输入法控制
