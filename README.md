# Homework 6
数字图像处理课程作业实验六

滤波器

## Author
王适未 自动化钱61 2160405015

## Exp. tasks
实验任务

1.在测试图像上产生高斯噪声lena图-需能指定均值和方差；并用多种滤波器恢复图像，分析各自优缺点；
2.在测试图像lena图加入椒盐噪声（椒和盐噪声密度均是0.1）；用学过的滤波器恢复图像；在使用反谐波分析Q大于0和小于0的作用；
3.推导维纳滤波器并实现下边要求；
(a) 实现模糊滤波器如方程Eq. (5.6-11).
(b) 模糊lena图像：45度方向，T=1；
(c) 再模糊的lena图像中增加高斯噪声，均值= 0 ，方差=10 pixels 以产生模糊图像；
(d) 分别利用方程 Eq. (5.8-6)和(5.9-4)，恢复图像；并分析算法的优缺点.

## File structures
文件结构说明

```
dist/
    hw6.md
    hw6-1.png
    hw6-2.png
    hw6-3.png
src/
    pic/
        test1.pgm
        test2.tif
        test3_corrupt.pgm
        test4 copy.bmp
        test4.tif
    hw6.m
.gitignore
README.md
hw6.md
hw6.txt
```

- The `dist/` directory contains all complied reports and pictures.
- The `src/` directory contains all source code and source pictures.
- The `hw6.md` file is the homework 6 report file, same as `dist/hw6.md`.
- The `hw6.txt` file is the homework 6 code file, same as `src/hw6.m`.
