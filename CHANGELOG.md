# 更新日志

## 3.0.3 - 2021/04/14

- 更细致的识别手机厂商及其品牌，增加荣耀、红米、爱酷、真我等品牌的支持。

## 3.0.2 - 2021/04/08

- 小米手机获取OAID问题 [@andot PR#18](https://github.com/gzu-liyujiang/Android_CN_OAID/pull/18)
- 增加数字版权管理设备ID
- 增加各大手机厂商关于OAID的说明文档
- 允许判断设备是否支持OAID [@andot PR#19](https://github.com/gzu-liyujiang/Android_CN_OAID/pull/19)

## 3.0.1 - 2021/03/29

- 增加设备标识符统一格式为MD5或SHA1的方法

## 3.0.0 - 2021/03/26

- 移除之前版本已废弃的方法，重构部分API
- 支持在应用启动时预先获取设备的客户端标识
- 增加[JavaDoc](https://gzu-liyujiang.github.io/Android_CN_OAID/)，更新说明文档
- 移除Github Actions的CodeQL

## 2.1.1 - 2021/03/03

- 修复魅族手机获取OAID失败问题，增加魅族效果图

## 2.1.0 - 2021/01/19

- 增加IMEI/MEID、AndroidID、GUID等获取方法
- 优化文档及调整其他一些细节

## 2.0.0 - 2021/01/13

- Fixed #8 （Demo编译错误）
- 分包，解决和移动安全联盟SDK冲突问题
- 引入华为云真机调试方案
- 修正文档错误
- 修复Github Actions错误

## 1.0.2 - 2020/08/20

- 规避可能的闪退
- 使用Github Actions代替Travis-CI
- 更新说明文档

## 1.0.1 - 2020/07/15

- 取消不支持OAID时默认生成的GUID

## 1.0.0 - 2020/05/30

- 初始版本

