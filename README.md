# circuitjs1-zh

#### 介绍
功能强大的基于HTML5的电路模拟器，circuitjs1的中文版本。

#### 项目说明
本项目是国外开源项目circuitjs1的中文编译版本，可模拟绝大多数的电路，适合物理教学，并在原项目的基础上添加了中文语言包locale_zh.txt，可能存在翻译问题，请及时在issues中提出。
预计后期会实现云储存，协作编辑等更高级的功能。

原项目地址(Paul)：https://github.com/pfalstad/circuitjs1
原项目地址(Iain)：https://github.com/sharpie7/circuitjs1

#### 实际使用
详见 https://hgcserver.gitee.io/tools/CircuitJS1-for-giteepages/circuitjs.html
![pic](https://images.gitee.com/uploads/images/2020/0326/162944_c6495c86_906045.png "pic.png")

#### 集成API


```
.../circuitjs1.html?cct=<string> //从URL中加载电路
.../circuitjs1.html?startCircuit=<filename> //从"Circuits"目录中加载名为"filename"的电路
.../circuitjs1.html?startCircuitLink=<URL> //从指定的URL电路文件地址加载电路。
.../circuitjs1.html?whiteBackground=<true|false> //是否采用白色背景
.../circuitjs1.html?conventionalCurrent=<true|false> //是否采用常规电流方向
```