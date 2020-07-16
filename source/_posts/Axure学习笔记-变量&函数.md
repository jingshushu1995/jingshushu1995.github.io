---
title: Axure学习笔记-变量&函数
date: 2020-07-15 20:27:38
tags: Axure
cover: https://img.zcool.cn/community/01a6295f0ec2a8a801206621e997c6.jpg@1280w_1l_2o_100sh.jpg
coverWidth: 1280
coverHeight: 547
---

## 全局变量



## 中继器/数据集

## 元件

## 页面

## 窗口

## 鼠标指针

## 数字

## 字符串

## 数学

## 日期

* **【getDate()】** 从Date对象返回一个月中的某一天（1～31）
* **【getMonth()】** 从Date对象返回月份（1～12）
* **【getFullYear()】** 从Date对象以四位数字返回年份
* **【getHours()】** 返回Date对象的小时（0～23）
* **【getMinutes()】** 返回Date对象的分钟（0～59）
* **【getSeconds()】** 返回Date对象的秒数（0～59）

### 案例

**案例1：** 获取系统当前日期，格式为：yyy-MM-dd
`
[[Now.getFullYear()]]-[[Now.getMonth()]]-[[Now.getDate]] 
`
**案例2：** 获取系统当前日期，格式为：yyy/MM/dd
`
[[Now.getFullYear()]]/[[Now.getMonth()]]/[[Now.getDate]] 
`
**案例3：** 获取系统当前时间，格式为：HH:mm:ss
`
[[Now.getHours()]]:[[Now.getMinutes()]]:[[Now.getSeconds]] 
`

## 布尔

### 赋值运算符

* **【=】** 等于

### 算术运算符

* **【+】** 加法运算
* **【-】** 减法运算
* **【*】** 乘法运算
* **【/】** 除法运算
* **【%】** 取余运算

### 关于运算符

* **【==】** 等于
* **【!=】** 不等于
* **【>】** 大于
* **【<】** 小于
* **【>=】** 大于等于
* **【<=】** 小于等于
* **【&&】** 并且
* **【||】** 或者
* **【!】** 非