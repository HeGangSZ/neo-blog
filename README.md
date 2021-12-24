# neo-blog
Neo的网络日志

## 2021.12.25

### DevTools 实现原理与性能分析实战
https://mp.weixin.qq.com/s/H8iahg5WUOHXeRzvf0R01w  
纪要：概述了网页调试工具的发展历程，chrome devtools的实现架构，其中PC端可以调试移动端的实现很有启发：通过client-server模式，用websocket封装json数据在浏览器内核间进行数据传输处理，可以实现js执行、移动端画面回显到PC端等功能
