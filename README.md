# HA Bark
[![hacs_badge](https://img.shields.io/badge/HACS-Custom-41BDF5.svg)](https://github.com/hacs/integration)

适用于home assistant的插件，可通过hacs添加。

- 推送时，data额外支持level字段
```angular2html
推送中断级别。
critical: 重要警告, 在静音模式下也会响铃
active：默认值，系统会立即亮屏显示通知
timeSensitive：时效性通知，可在专注状态下显示通知。
passive：仅将通知添加到通知列表，不会亮屏提醒。
```