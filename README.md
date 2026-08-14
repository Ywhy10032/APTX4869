# APTX4869

用于直接控制 ANKNI YWTD BLE 设备的 Android 手机端与 OPPO Watch X2 手表端应用。

## 最新版本

- 手机端：v1.1.0
- 手表端：v1.0.0
- [前往发行版下载 APK](https://github.com/Ywhy10032/APTX4869/releases)

## 工程文件

- `APTX4869-Phone-Project-v1.1.0.zip`：手机端完整 Android 工程
- `APTX4869-Watch-Project-v1.0.0.zip`：手表端完整 Android 工程

工程压缩包已排除 `build`、`.gradle`、`.idea`、`local.properties`、诊断文件和测试截图等生成内容或本机配置。

## 手机端 v1.1.0 更新

- 浅色模式改为浅粉背景。
- 按钮使用玫粉、小鸡黄、天空蓝三种配色。
- 每次冷启动都会更换三种颜色的排列，并避免连续两次完全相同。
- 暗黑模式、水波切换、BLE 控制和电量显示保持不变。

## 安全说明

BLE 控制仅写入已经确认的 `0xDDD1` 控制特征，不包含固件升级操作。
