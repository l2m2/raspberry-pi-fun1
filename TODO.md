# TODO

## 供电
- [x] 用手机充电头 + 绿联 0.25m 短线供电，检查 `vcgencmd get_throttled` 是否为 `0x0`：已解决，见 `docs/troubleshooting.md` 第 5 条
- [ ] 采购移动电源方案：2 节 18650 + 带开关的电池盒 + 2S 充电器或保护板 + 5V 3A 降压模块（树莓派用）+ 5～6V 5A 降压模块或 UBEC（舵机用）

## 树莓派
- [ ] 开启 I2C（`sudo raspi-config` → Interface Options → I2C），确认出现 `/dev/i2c-1`

## 机械结构
- [ ] 用卡尺量东方树叶瓶口外径和螺距，用于画瓶口转接件的 OpenSCAD 模型
- [ ] 做 3 节瓶子 + 2 个舵机的蛇形小样，验证连接强度、瓶身变形和供电稳定性

## 控制
- [ ] 采购 PCA9685 舵机驱动板和舵机（SG90 / MG90S）
- [ ] 编写 PCA9685 蛇形步态的 Python 控制代码
