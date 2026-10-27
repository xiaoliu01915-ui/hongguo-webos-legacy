# 红果短剧 · LG webOS 老款电视兼容版

基于 [aston314/hongguo-tv-releases](https://github.com/aston314/hongguo-tv-releases) 的 webOS 安装包修改，面向使用原版时遇到连接超时、播放解析问题的老款 LG 电视。

这是由 **xiaoliu01915-ui** 发布的第三方兼容测试版，与原作者的官方发布独立维护。感谢 **aston314** 提供原项目。

## 下载

[前往 Releases 下载安装包](https://github.com/xiaoliu01915-ui/hongguo-webos-legacy/releases)

当前兼容包：`hongguo-webos-0.2.121-test.25-node012-fix.8.ipk`

请下载 Release 附件中的 **.ipk** 文件；GitHub 自动生成的 Source code 压缩包不是电视安装包。

## 主要修复

- 修复老款 LG 电视上的连接超时问题。
- 修复播放解析问题。

以上为本兼容版维护者说明。不同型号、固件和网络环境的实际表现请自行测试。目前没有公开确认的完整支持型号列表或最低 webOS 版本，不保证所有老款 LG 电视都能正常运行。

## 安装

1. 在 LG 电视上启用 Developer Mode（开发者模式）。
2. 使用 webOS Dev Manager 或 LG webOS 开发工具连接电视。
3. 选择下载的 `.ipk` 文件进行安装，然后启动应用测试。

本包只适用于 LG webOS TV，不能当作 Android APK 安装。

**安装前请注意：** 本包保留上游应用 ID `com.aston314.hongguo.webos`，内部应用版本为 `0.2.121`。安装时可能覆盖同 ID 的原版应用，不能依靠文件名将两版并排安装；如已安装更高内部版本，也可能出现版本限制。请先记录需要保留的信息。

## 更新说明

本仓库通过 Releases 手动提供兼容包。当前包内“检查更新”仍指向上游发布渠道，那里提供的版本不代表本仓库的老款电视兼容版。需要保留本版修复时，请手动下载本仓库附件，并确认版本后再更新。

## 问题反馈

请在[本仓库 Issues](https://github.com/xiaoliu01915-ui/hongguo-webos-legacy/issues)反馈，尽量提供：

- LG 电视完整型号、webOS / 固件版本。
- 安装包文件名及安装、启动是否成功。
- 连接超时或播放解析失败的具体步骤与提示。
- 画面、声音、切集情况，以及必要的截图。

请勿提交账号密码、验证码或其他个人敏感信息。欢迎反馈测试通过的型号。

## 文件校验

安装包大小：**1,192,110 字节**

SHA256：

```text
f4e93174c497059f8bcbb62e76c64a593261d8763214040694a4bc542e696d60
```

Release 同时提供 `SHA256SUMS.txt`。本次发布保留维护者提供的安装包原样，未重新打包。

## 项目来源与许可说明

- 上游项目：[aston314/hongguo-tv-releases](https://github.com/aston314/hongguo-tv-releases)。
- 原项目及第三方组件的权利属于各自权利人；安装包内保留了原有作者信息和第三方许可文件。
- 本仓库用于发布兼容安装包与说明，目前不包含完整开发源码。
- 未给整个上游应用另行声明 MIT、Apache 等开源许可；包内第三方组件的许可不等于整个应用的许可。
