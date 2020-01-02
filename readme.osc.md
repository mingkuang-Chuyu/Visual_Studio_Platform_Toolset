# Visual Studio平台工具集

- [English](readme.md)

## 1. 关于平台工具集
某些时候，一些上古的工程可能无法简单迁徙。但是我们又希望能使用新的IDE，比如说Visual Studio 2019。平台工具集能满足我们这方面需求，即使用新IDE编写代码，用老编译器以及库编译生成代码。

此外，对于编译器无关的新功能也能正常使用，比如说NuGet。

> 由于内容都是二进制文件，因此请直接下载二进制包。

### 1.1. 原理
微软本身就支持，我只是大自然的搬运工。方便大家快速整合工具集，免去数小时的安装时间。


## 2. 平台工具集

### 2.1. Visual Studio 2008(v90) 平台工具集
##### 2.1.1. 兼容性
仅支持x64操作系统，目前已知兼容以下IDE：
* Visual Studio 2010
* Visual Studio 2012
* Visual Studio 2013
* Visual Studio 2015
* Visual Studio 2017
* Visual Studio 2019

#### 2.1.2. 使用方法
1. 从[Release](https://github.com/mingkuang-Chuyu/Visual_Studio_Platform_Toolset/releases/latest)中下载平台工具集二进制文件。
2. 安装.NET 3.5（Windows 8以及更高版本因为不自带，因此请先自行安装）
3. 将压缩包内文件夹剪切到 C 盘。
4. 双击 `VC2008.reg`。
5. 启动新IDE，在项目属性 - 常规 - 平台工具集 - Visual Studio 2008(v90) 编译代码。

## 更新日志

### v1.0.2 2020-01-02
* 删除 Visual Studio 2008 平台工具集内一些无用文件。
