# 双目立体匹配_SGM算法资源文件介绍

## 资源描述

本仓库提供了一个关于双目立体匹配中SGM（Semi-Global Matching）算法的资源文件。该资源文件详细记录了在KITTI2015数据集上使用SGM算法进行立体匹配的测评结果。

## 开发环境

- **Python版本**: 3.6
- **NumPy版本**: 1.19.5
- **OpenCV版本**: 4.5.5.64
- **操作系统**: Ubuntu 20.04 LTS
- **处理器**: Intel(R) Core(TM) i7-9700 CPU @ 3.00GHz

## 实验记录

以下是不同策略和参数设置下的实验结果：

1. **WTA、SSD策略**
   - **视差范围**: 190
   - **半径**: 3
   - **视差精度**: 0.5611
   - **运行时间**: 7.4344秒

2. **WTA、SSD策略**
   - **视差范围**: 64
   - **半径**: 3
   - **视差精度**: 0.5611
   - **运行时间**: 2.7495秒

3. **SGM、SSD策略**
   - **视差范围**: 64
   - **半径**: 3
   - **视差精度**: 0.8161
   - **运行时间**: 22.7137秒

4. **SGM、NCC策略**
   - **视差范围**: 64
   - **半径**: 3
   - **视差精度**: 0.8119
   - **运行时间**: 28.0640秒

5. **SGM、SAD策略**
   - **视差范围**: 64
   - **半径**: 3
   - **视差精度**: 0.6681
   - **运行时间**: 22.3349秒

## 结论

通过上述实验记录可以看出，SGM算法在不同策略下的表现有所不同。总体而言，SGM算法在视差精度上表现较好，但运行时间相对较长。具体选择哪种策略和参数设置，可以根据实际需求进行调整。

## 下载链接

[双目立体匹配_SGM算法资源文件介绍](https://pan.quark.cn/s/b57ba5bf749e)