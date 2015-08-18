# 对于云POS各厂商
## 设计总体原则
1. 扩展性
增加额外设备不影响已有API
2. 兼容性
设备具有额外功能时，用户不用关心额外功能

## 总体要求
+ 获取终端型号和OS版本号
+ 设备发现
+ 可以判断机器中是否存在某个设备
+ 罗列机器中的所有设备
+ 接口版本管理
+ 设备特性获取
+ 获取设备具有的特性信息
+ 支持异步操作

## 总体框架
 ![image](https://github.com/ZhangUP/CloudposSDK/docs/何总总体框架图.png)
