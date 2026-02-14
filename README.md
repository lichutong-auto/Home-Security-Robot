# Home-Security-Robot
A home security robot project for competition, based on Arduino/ESP32.
# 家庭安防巡逻机器人

> 一个基于Arduino/OpenMV的自主移动机器人项目，用于学习与实践自动控制、传感器融合技术，目标参加省级机器人创意大赛。

## 🎯 项目特性
- 自主巡逻与避障
- 多传感器融合（视觉、超声波）
- 模块化设计，便于扩展

## 🏗️ 硬件架构
- 主控：Arduino UNO R3
- 视觉：OpenMV / K210
- 驱动：L298N电机驱动模块
- 传感器：超声波、红外等

## 🧩 软件架构
- 底盘控制：Arduino C++ (PID控制)
- 视觉处理：Python/OpenMV
- 通信：串口/UART

## 🚀 快速开始
1. 克隆仓库：`git clone https://github.com/yourname/Home-Security-Robot.git`
2. 硬件连接：详见 [硬件接线图](hardware/schematic/pinout.png)
3. 上传固件：打开 `firmware/motor_control/src/main.ino` 用Arduino IDE上传
4. 运行视觉：`cd firmware/vision_sensor && python main.py`

## 📁 项目结构

## 👥 团队成员
- **李储同** - 驱动与控制 (`firmware/motor_control/`)
- **魏宏阳** - 视觉与感知 (`firmware/vision_sensor/`)

## 📄 文档
- [项目概述](docs/project_overview.md)
- [通信协议](docs/api/serial_protocol.md)
- [组装指南](docs/tutorials/assemble_guide.md)
