# python数据分析

## python基础 

### 推荐三本数据分析入门的书

* 对比Excel,轻松学习Python数据分析（入职数据分析师系列） 张俊红

* python数据分析从入门到精通（明日科技）

* 数据分析:企业的贤内助（职业思维的培养）

### 编程语法巩固网站

* https://www.lintcode.com/problem/?typeId=8 python入门题目(184题目，6周完成120道题目)
* https://www.runoob.com/python3/python3-list.html  上课同步参考网站菜鸟教程 
* https://github.com/shixiuhai/dataAnalysis.git  git仓库地址

## 学习安排（2月）

* 第一周学 基础数据类型 2.5 h
* 第二周学 条件控制和循环函数2.5 h
* 第三周 巩固条件控制和循环2.5 h
* 第四周 编程题讲解2.5 h
* 第五周 pandas和matplotlib numpy 基础2.5 h
* 第六周 餐厅订单数据分析项目 或者python批量处理excel文件2.5 h
* 第七周 完善餐厅订单项目和开始物流行业醒目2.5 h
* 第八周 完善物流行业项目以及总结 2.5h

### 开始python的学习

* 计算机语言概览

  * 编程语言的发展
  * 什么是编程语言
  * 常用的编程语言有哪些
    * 常用使用较为广泛的编程语言(python、java、go、c、c++、js、php)
  * 编程语言能做哪些事情
  * python语言方向
    * 数据分析
    * 数据挖掘
    * 人工智能
    * 数据爬虫
    * web开发
    * 运维开发
    * 大数据
    * 机器视觉

* python环境搭建

  * 经典的开发环境配置
  * 虚拟环境使用
    * 基于python的虚拟环境，可以实现项目依赖隔离
    * 基于anaconda构建python和依赖的虚拟环境（数据分析基本可以不用）
  * 基于anaconda安装 jupyter notebook
    * 跳过
  * 基于vscode 使用jupyter notebook
    * 下载安装vscode
    * 配置一下python的插件
    * 配置jupyter notebook环境

* python基础语法

  * 编程语言的解释器是什么
  * 编译器和解释器的区别

  * python基于缩进来隔离逻辑
  * python变量命名规则
    * 驼峰命名法
    * 下划线命名法

* python注释

  * 单行注释
  * 多行注释

* python基本数据类型（常见）

  * int
  * float
  * str
  * doule

* python其他数据类型

  * 列表（用的较多）

    * 增删改查

      ```bash
      # 元素的增加
      test_list=[]
      test_list.append(1)
      # 元素的删除
      # 元素的修改
      # 元素的查询
      ```

    * 元素数量统计

      ```python
      print(len(test_list))
      ```

      

  * 元组

    * 元组使用

  * 字典（用的较多）

    * 字典使用

  * 集合

    * 去重实现

* python函数

  * 什么是函数
* 怎么实现函数
  * 程序员常说的技术栈和框架是什么

* python循环

  * while 循环
  * for 循环

* python条件控制

  * if elif else
  * **match...case**跳过
  * 三目运算符  跳过 

* python 字符串操作
  * 字符串切片
  * 字符串分割
  
* python基本运行符
  * 加
  * 减
  * 乘
  * 除
  * 取余
  * 指数
  * 平方根
  
* python文件操作
  * python打开关闭txt
  * python打开文件二进制流

* 测验题目
  * 水费梯度（条件控制掌握）
  * 出租车车费梯度（条件控制掌握）
  * 修改二维矩阵的数值（分析数据用到的最高维度数组）
  * 通过python实现简单的计算器功能（循环和条件控制的使用）
  * 水仙花数或者厉害数的寻找（循环和条件控制使用）

## pandas基础

* 读取数据文件
  * excel 读取
  * csv读取
  * txt读取
* 对空值进行处理
  * 0数值或者NAN值处理
* 对数据进行行列操作
  * 合并，求和，平均值
* 常用方法
  * loc
  * iloc

## matplotlib基础

* 直线图
  * 反映x和y变量的关系
* 折线图
  * 反映事物变化趋势
* 条形图
  * 直观展示不同类别的差异性
* 直方图
  * 表示同一个类型在不同区间的差异性

## 入门项目

* 通过读取多个excel文件进行跨文件的数据进行处理
* 餐厅订单数据分析
* 物流行业数据分析
* 豆瓣电影数据分析
* pm2.5案例

