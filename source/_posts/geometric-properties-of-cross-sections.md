---
title: 截面的几何性质
date: 2022-11-19 16:59:30
tags: 笔记
categories: 材料力学
mathjax: true
---

## 静距和形心

### 定义

$S_z$ 表示截面到 $z$ 轴的静距， $y_C$ 表示形心的 $y$ 轴坐标．

静距的量纲为长度的 3 次方．

截面对某个轴线的静距是微元面积与其到该轴线距离的乘积的积分，即

$$S_y=\int\limits_{A} z\mathrm d A$$

$$S_z=\int\limits_{A} y\mathrm d A$$

### 定理

由**合力矩定理**可得

$$z_C=\frac{S_y}{A}, y_C=\frac{S_z}{A}.$$

故我们有

$$S_y=z_CA, S_z=y_CA.$$

如果我们选择的**坐标轴**穿过了形心，则其称作**形心轴**．此时 $z_C$ 或 $y_C$ 为 $0$ ．又 $A$ 不为 $0$ ，所以 $S_y$ 或 $S_z$ 为 $0$．即有定理：**若坐标轴是形心轴，则截面对其静矩为 $0$**．其逆命题也成立．

### 计算

若界面形状由多个基本图形组成，则形心坐标为各图形静距之和与各图形面积之和的比值．

实际计算中，可以记住基本图形的公式，无需通过积分求．

#### 矩形的静距

矩形的静距为长、宽、矩形形心到轴距离三者的乘积：

$$S_z=bh\cdot\frac 1 2 h=\frac 1 2 bh^2.$$

## 惯性矩

### 定义

惯性矩的量纲为长度的 4 次方．

截面对某个轴线的惯性矩是微元面积与其到该轴线距离 2 次方乘积的积分，即

$$I_{z}=\int\limits_{A} y^{2} \mathrm{~d} A$$

$$I_{y}=\int\limits_{A} z^{2} \mathrm{~d} A$$

### 计算

#### 矩形的惯性矩

对 $z$ 轴

$$I_z=\frac{bh^3}{3}$$

其中， $b$ 为宽， $h$ 为高．

对形心轴

$$I_z=\frac{bh^3}{12}$$

#### 圆的惯性矩

对形心轴

$$I_z = \frac{\pi D^4}{64}$$

#### 圆环的惯性矩

$$I_z = \frac{\pi D^4(1-{\frac d D}^4)}{64}$$

其中， $d$ 为内环直径， $D$ 为外环直径．

#### 三角形的惯性矩

$$I_z = \frac{bh^3}{36}$$

其中， $b$ 为底边长， $h$ 为高．

### 定理

由**平行轴定理**，对**转动惯量**，我们有

$$I_{z'}=I_C+Md^2$$

其中， $M$ 为刚体质量．

对惯性矩，我们也有

$$I_z = I_x + Ad^2$$

## 极惯性矩

### 定义

截面对于一个轴的**极惯性矩**，又称**截面二次极矩**，是截面上微元面积与其到坐标原点距离 2 次方乘积的积分，即

$$I_p = \int\limits_A\rho^2\mathrm d A$$

其中， $\rho$ 为微元距轴的距离．

有

$$I_p = \int\limits_A\rho^2\mathrm d A=\int\limits_A(z^2+y^2)\mathrm d A=I_y+I_z.$$

以上．🪵
