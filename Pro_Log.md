# STM32Fxx_HAL_Model
Many STM32Fxx Pro Model

## 2018-6-27

使用STM32cube创建的项目，出项问题：

1. 创建的项目不能在工程中添加文件夹
    >解决方法：删除文件夹下cube文件。
2. 创建的工程添加hal库的.c文件（源文件）后，但是在编译后.h（头文件）不能同步，不知道为什么。
    >解决方法：以后只能尽量把资源规划好在创建工程，（不用在乎引脚，只要把通道打开就可以了）
  
## 2018-6-28
创建了STM32F407ZGHAL库的模板工程。
