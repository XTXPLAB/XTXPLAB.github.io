---
title: 魏肖彤《Near-Threshold RISC-V Core With DSP Extensions for Scalable IoT Endpoint Devices》
categories:
- 论文分享
tags:
- 论文分享
- 数字电路
- RISC-V
- 计算机体系结构
---

# 2021-12-4论文分享
魏肖彤《Near-Threshold RISC-V Core With DSP Extensions for Scalable IoT Endpoint Devices》
适用于物联网终端设备，该文章针对紧耦合多核架构的近阈值操作条件，设计一款开源riscv处理器核。为了增加计算密度和最小化访问共享存储单元的负担，进行处理器指令扩展和微架构优化。

![魏肖彤论文分享1-1](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-1.png)

## 论文摘要与导言

![魏肖彤论文分享1-2](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-2.png)

![魏肖彤论文分享1-3](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-3.png)

![魏肖彤论文分享1-4](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-4.png)

![魏肖彤论文分享1-5](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-5.png)

![魏肖彤论文分享1-6](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-6.png)

![魏肖彤论文分享1-7](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-7.png)

## 创新点

![魏肖彤论文分享1-8](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-8.png)

![魏肖彤论文分享1-9](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-9.png)

![魏肖彤论文分享1-10](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-10.png)

![魏肖彤论文分享1-11](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-11.png)

![魏肖彤论文分享1-12](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-12.png)

![魏肖彤论文分享1-13](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-13.png)

![魏肖彤论文分享1-14](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-14.png)

![魏肖彤论文分享1-15](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-15.png)

![魏肖彤论文分享1-16](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-16.png)

![魏肖彤论文分享1-17](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-17.png)

![魏肖彤论文分享1-18](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-18.png)

![魏肖彤论文分享1-19](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-19.png)

![魏肖彤论文分享1-20](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-20.png)

![魏肖彤论文分享1-21](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-21.png)

![魏肖彤论文分享1-22](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-22.png)

![魏肖彤论文分享1-23](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-23.png)

![魏肖彤论文分享1-24](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-24.png)

![魏肖彤论文分享1-25](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-25.png)

## 实验分析

![魏肖彤论文分享1-26](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-26.png)

![魏肖彤论文分享1-27](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-27.png)

![魏肖彤论文分享1-28](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-28.png)

![魏肖彤论文分享1-29](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-29.png)

![魏肖彤论文分享1-30](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-30.png)

![魏肖彤论文分享1-31](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-31.png)

![魏肖彤论文分享1-32](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-32.png)

![魏肖彤论文分享1-33](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-33.png)

![魏肖彤论文分享1-34](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-34.png)

![魏肖彤论文分享1-35](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-35.png)

![魏肖彤论文分享1-36](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-36.png)



## 结论

![魏肖彤论文分享1-37](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-37.png)

![魏肖彤论文分享1-38](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-38.png)

![魏肖彤论文分享1-39](https://raw.githubusercontent.com/XTXPLAB/XTXPLAB.github.io/main/imgs/%E9%AD%8F%E8%82%96%E5%BD%A4%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB1-39.png)