# GCC-for-openEuler-exploration
### 团队介绍
贾柯 宋冠喆 曹泽阳 王旭博 王钟强
### 项目内容
![image](https://github.com/user-attachments/assets/9aad8a01-3c39-4fb7-9909-b5319ba71823)
### 项目架构
#### GCC for openEuler的基础知识背景探索与总结
#### GCC for openEuler的基础特性分析
#### 实验验证GCC for openEuler的性能提升优化
#### 设计凸显GCC for openEuler特性的应用场景案例
redis benchmark on openEuler, Ubuntu, CentOS.

Architecture: Kunpeng

Hardware Spec: 2CPU 8GiB

CFLAGS=" -O3 -march=armv8.1-a -flto -floop-crc -mcmlt-arith -fcrypto-accel-aes -fipa-prefetch -fipa-ic -fuaddsub-overflow-match-all -ftree-fold-phiopt"

### 项目总结
本次项目基于GCC for openEuler的性能特点及其优化特性，在项目进行的过程中，我们开展了一系列的性能测试和对比分析，发现了在特定应用场景下，GCC可以通过合理的编译选项与优化策略，显著提升程序的执行效率。这不仅增强了我们对编译器优化技术的理解，也激励我们在今后的研究中继续探索更为高效的编译算法。期待能够将这些经验和技术应用于更广泛的项目中。 



