# AnotherMiraiNative（AMN）
来了，又是一个酷Q兼容项目

## 特点
相较于`Mirai-Native`具有以下特点：
- 由插件异常导致程序崩溃时，不会导致`Mirai`框架崩溃
- 图形化界面
- 可对单个插件重载
- 可对单个插件进行消息逻辑测试，省去在群内发消息
- 服务器端可使用64位的JRE了

## 依赖
- .netframework48
- mirai-api-http v2

## 安装与配置mirai-api-http
https://github.com/project-mirai/mirai-api-http#安装mirai-api-http
- 开放`ws`，配置`verifyKey`
- 如需公网访问，请将`ws-host`设置为`0.0.0.0`，服务器开放ws的监听端口

## 待实现功能
- [ ] WebUI
- [ ] 糊的所有功能真的可用吗？

## 已知的问题
- 插件初始加载，点击启用时会有文件占用提示
- 禁言事件无法触发
- 事件日志不完备
- 没有发送音频支持
- 函数调用失败时，没有对应提示，比如bot被禁言、发送消息至未加入的群等
- 日志窗口无法调整尺寸