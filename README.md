# 鲁棒音频信息隐藏工具箱

`audio-stego-lab` 是一个信息隐藏与网络空间安全方向的可运行开源项目，包含核心算法代码、命令行入口、实验配置、示例脚本和 smoke tests。

## Overview

本项目面向音频载体中的信息隐藏实验与教学开发，提供音频预处理、秘密消息编码、嵌入强度控制、鲁棒性攻击模拟和提取验证等模块。系统支持 WAV/FLAC 等常见格式，可对比最低有效位嵌入、扩频嵌入、回声隐藏和频域嵌入等方法，并输出信噪比、误码率、听觉质量等指标。项目适合用于信息隐藏课程实验、论文复现实验和音频水印原型验证，便于学生在统一接口下扩展新的嵌入算法与攻击评估流程。

## Features

- 统一的数据加载、实验配置和结果保存流程
- 面向信息隐藏/数字水印/隐写分析任务的模块化设计
- 支持实验指标输出、样例结果归档和后续算法扩展
- 适合课程实验、毕业设计、论文复现实验和课题组日常开发

## Quick Start

```bash
python examples/demo.py
python -m unittest discover -s tests
python -m audio_stego_lab.cli --message "demo payload" --report docs/cli_report.md
```

## Keywords

audio steganography · watermark · robustness · signal processing

## Authors

- 负责人：林裕斌
- 参与人：曾科、田承金
- 指导教师：吕善翔
- 单位：暨南大学网络空间安全学院

## License

本项目建议采用 MIT License；实际开源时请根据课题组要求确认许可证。
