# ACEBit

> 面向 ACEBOTT ACEBit V2.0 扩展板的 BBC micro:bit Microsoft MakeCode 扩展。

## 主要功能

- 控制 4 路直流电机
- 控制 180°、270° 和 360° 舵机
- 控制 28BYJ-48 步进电机
- 控制板载 RGB 灯
- 播放 micro:bit 内置旋律
- 通过 PCA9685 提供多通道 PWM 输出

## 安装

1. 打开 [Microsoft MakeCode for micro:bit](https://makecode.microbit.org/)。
2. 新建项目并进入“扩展”。
3. 搜索以下仓库地址并导入：

```text
https://github.com/September535/ACEBit
```

## 快速开始

```typescript
ACEBit.MotorRun(ACEBit.enMotors.M1, 120)
basic.pause(1000)
ACEBit.MotorStopAll()
```

电机速度范围为 `-255` 到 `255`，正负值代表相反方向。连接电机或舵机前，请先确认扩展板端口和供电要求。

## 支持平台

- BBC micro:bit
- Microsoft MakeCode / PXT
- ACEBOTT ACEBit V2.0

## 开发

在 MakeCode 中依次选择“导入”→“导入 URL”，粘贴本仓库地址即可编辑扩展。

## 许可证

MIT
