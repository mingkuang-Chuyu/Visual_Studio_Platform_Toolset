# Visual Studio Platform Toolset

- [简体中文](readme.osc.md)

## 1. About Platform Toolset
Sometimes, some ancient projects may not be able to simply migrate. But we also want to use a new IDE, such as Visual Studio 2019.
The platform toolset can meet our needs in this regard, that is, use the new IDE to write code, use the old compiler and libraries to generate code.

In addition, compiler-independent new features can also be used normally, such as NuGet.

> Since the contents are binary files, please download the binary package directly.

### 1.1. ABC
Microsoft itself supports it, I'm just a porter of nature. It's easy for everyone to quickly integrate the toolset and save hours of installation time.


## 2. Platform Toolset

### 2.1. Visual Studio 2008(v90) Platform Toolset
#### 2.1.1. Compatibility
Only supports x64 operating system, currently known to be compatible with the following IDEs：
* Visual Studio 2010
* Visual Studio 2012
* Visual Studio 2013
* Visual Studio 2015
* Visual Studio 2017
* Visual Studio 2019

#### 2.1.2. Instructions
1. Download the platform toolset binary from [Release](https://github.com/mingkuang-Chuyu/Visual_Studio_Platform_Toolset/releases/latest).
2. Install .NET 3.5 (Windows 8 and later are not included, so please install it yourself).
3. Extract the folders in the compressed package to the C drive.
4. Double click `VC2008.reg`.
5. Start the new IDE and compile the code in Project Properties - General - Platform Toolset - Visual Studio 2008(v90).

## Change Log

### v1.0.2 2020-01-02
* Delete some useless files in the Visual Studio 2008 platform toolset.