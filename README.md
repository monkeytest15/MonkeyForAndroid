这是一个Android性能自动化测试工具Monkey For Android
=================================================

已经实现
--------
1. 模拟用户随机操作
2. CPU和内存占用性能数据抓取
3. 固定测试时间

TODOs
-------
1. 完善控件抓取精确度
2. 完善异常处理
3. 性能数据：电池消耗和流量的抓取
4. 抓取所有可点击控件，并随机点击

User Guide
----------
###一． PC环境配置
1. 安装手机驱动。
2. 安装jdk 1.6 或以上版本，tools目录下有jdk安装文件，并配置环境变量。
3. 配置adb环境，把Monkey目录tools下面的adb.exe文件配置到环境变量。

###二．Monkey运行步骤：
1. 在conf.xml文件里面配置monkey运行参数
   按照conf.xml文件里面的注释配置好所有参数
2. 把应用APK包放进Monkey根目录
3. 执行Monkey.bat文件
4. 搜集结果
a. log.txt文件（Monkey 运行输出日志）
b. cpu.jpg（CPU折线图）
c. mem.jpg（内存折线图）
d. *.csv文件（CPU和内存数据）
