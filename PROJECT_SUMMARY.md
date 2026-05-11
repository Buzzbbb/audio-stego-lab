# 鲁棒音频信息隐藏工具箱

英文名称：`audio-stego-lab`

开源地址：`https://github.com/Buzzbbb/audio-stego-lab`

项目时间：2024年9月-至今

## 作者信息

- 负责人：林裕斌，专业：网络空间安全，硕士生
- 参与人：曾科，专业：网络空间安全，硕士生
- 参与人：田承金，专业：网络空间安全，硕士生
- 指导教师：吕善翔，网络空间安全学院教师

## 项目内容

本项目面向音频载体中的信息隐藏实验与教学开发，提供音频预处理、秘密消息编码、嵌入强度控制、鲁棒性攻击模拟和提取验证等模块。系统支持 WAV/FLAC 等常见格式，可对比最低有效位嵌入、扩频嵌入、回声隐藏和频域嵌入等方法，并输出信噪比、误码率、听觉质量等指标。项目适合用于信息隐藏课程实验、论文复现实验和音频水印原型验证，便于学生在统一接口下扩展新的嵌入算法与攻击评估流程。

## 影响力

项目开源后可作为音频隐写与数字水印方向的实验基础，支撑课题组课程实验、毕业设计和论文复现实验，便于后续研究者复用统一的数据处理与评测流程。

## 开发语言

Python

## 代码规模

1012行（按当前项目 src/tests/examples 下 Python 代码统计）

## 建议仓库结构

```text
audio-stego-lab/
├── README.md
├── LICENSE
├── PROJECT_SUMMARY.md
├── src/
├── examples/
├── tests/
├── docs/
└── screenshots/
```

## 截图材料

- 项目目录截图：`screenshots/directory.png`
- 项目说明截图：`screenshots/readme.png`
- 项目声明截图：`screenshots/license.png`

## 关键词

audio steganography, watermark, robustness, signal processing
