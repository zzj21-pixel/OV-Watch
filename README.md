
## 编译环境
- IDE：Keil MDK
- 芯片包：STM32F4系列器件库
- 编译工具：ARM Compiler

## 烧录与升级
1. 下载工程代码，使用Keil MDK打开 `.mxproject` 工程文件
2. 编译生成固件 `.hex`
3. 可使用ST-Link下载固件；项目自带IAP，支持蓝牙在线升级

## 开发说明
- master分支：稳定基础版本，用于保存基准源码
- 建议新建dev分支做新功能开发，测试完成后合并至master
- 底层BSP驱动解耦，可单独修改屏幕、蓝牙、按键、电源相关代码

## License
本项目遵循仓库内 LICENSE 文件协议。
