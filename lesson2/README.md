<< [返回到上一层](../README.md) 

```
第0堂课任务
1，进度总结表
[链接地址]
2，lesson0.1(基础)
[链接地址]
3，lesson0.2(进阶)
[链接地址]
4，仓库链接
[链接地址]
```

# lesson 2

## lesson 2.1 初步搭建工程与Git使用

## lesson 2.2 项目流程与工程创建

一个典型的工程目录

```
00_ProjManagement --项目规划
01_Reference --参考资料 芯片手册，器件手册
02_FunctionMap --功能规划和开发节点
03_Hardware --硬件 原理图，PCB,BOM物料清单
04_Firmware --固件，比如Bootloader，其他中间件如HAL,Drivers等
05_Software --应用层软件（如上位机软件/移动端app/云平台），算法开发
06_Mechanical --CAD/3D模型
07_FCT --Functional Test，功能测试用例，自动化脚本等
08_Tools --软件工具，测试调试工具，辅助开发脚本，批量烧录工具
README.md
```

`00_ProjManagement` 项目规划

```
00_需求导入QFD
01_需求约束Pugh
02_需求转化
03_功能图谱 --
04_法规认证 
05_知识产权审查与规划
06_功能风险管控DFMEA  --冗余设计，风险应对措施
07_敏捷开发Scrum
08_持续集成与测试DevOps --自动化测试模拟
09_量产产品生产管理SixSigma --生产端
10_缺陷管理追踪Jira --跟踪产品项目缺陷
```

对于个人项目来说

```
00_需求导入QFD
03_功能图谱
07_敏捷开发Scrum
```

对于小团队（≈10）项目来说

```
00_需求导入QFD（简化）
01_需求约束Pugh（简化）
03_功能图谱
06_功能风险管控DFMEA --对核心功能的失效分析
07_敏捷开发Scrum（简化）
```





## Q&A

1. 为什么时钟源配置时，要用另一个定时器作为系统时钟？

答：

2. 串口通信时的 GND 是否一定要接？VCC 是否一定要接？

答：

3. 什么是 printf 的重定向？

答：

4. 串口是否有起始位？如果有，是怎么样的？

答：

5. 什么是 `git stash` ， 什么时候会使用 `git stash`, `git stash pop`?

答：

6. RCC 和 SYS 好像都是配置时钟，有什么区别吗？

答：

7. 使用printf为什么要勾选Microlib？ 什么是半主机模式？[微库 & 断言 & (Keil)代码优化](https://shatang.github.io/2020/05/30/微库-断言-Keil-代码优化/)

答：


---

<< [返回到上一层](../README.md) ##  < [查看上一节 lesson0/README.md](../lesson0/README.md) | [查看下一节 lesson2/README.md](../lesson2/README.md) >

...