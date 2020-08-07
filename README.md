# Cache-Lab-CSAPP

## 背景
* 课程：System programming
* 教材：  Computer Systems: A Programmer's Perspective (CSAPP)

## 语言
C

## 环境与使用
linux下给定的实验环境
* 创建 `csim.c`文件并加入code
* 执行 `make`，输出结果

## 实验步骤
Part 1: 
利用所学到的缓存知识，制作一个缓存系统（模拟环境）
* 在给定的环境中实现一个缓存模拟器
* 对目标文件 `trace` 进行对应的操作（Least Recently Used) ，输出结果

Part 2:
利用缓存机制转制矩阵，加速矩阵运算
* 对 32 x 32， 64 x 64, 和 61 x 67 三种矩阵进行测试
* 使用 cache blocking 提高运算速度

## 总结
* 因为这在之前的lab都是汇编语言，所以在这次实验中，更能体会到高级编程语言的可贵之处。 
* 具现化了locality这个抽象的概念
* 非常具现化的感受到了缓存系统的设计，原理和实现方式。
 
