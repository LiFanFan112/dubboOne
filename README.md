# Dubbo demo project

## 整体架构
<img src="https://github.com/LiFanFan112/dubboOne/blob/master/1.png" width="950" alt="整体架构"/>

## SpringBoot构建多模块项目
<img src="https://github.com/LiFanFan112/dubboOne/blob/master/3.png" width="950" alt="模块架构"/>

## dubbo两大协议 
### 1 RPC/Dubbo协议：同构项目(同种结构)-直接引入其他服务的api-犹如本地调用

显示商品列表功能：商品平台服务 调用 商品列表服务
<img src="https://github.com/LiFanFan112/dubboOne/blob/master/2.png" width="950" alt="Duboo协议架构"/>

### 2 Http协议rest api:通用项目~通用解析

下单功能：商品平台服务 调用 下单功能
<img src="https://github.com/LiFanFan112/dubboOne/blob/master/4.png" width="950" alt="Http架构"/>
