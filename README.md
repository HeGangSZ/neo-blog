# neo-blog
Neo的网络日志

## 2022.01.25

### 腾讯课堂 H5 直播间点赞动效实现
https://mp.weixin.qq.com/s/wGQ-Dwg4wERTnBmPhj0hsQ  
纪要：可以通过css和canvas两种形式实现点赞，点赞是直播间的必备功能，mark


## 2022.01.02

### Webpack 性能系列四：分包优化
https://mp.weixin.qq.com/s/LrASIdA19iwIwng29G5HpA  
纪要：详述了webpack4里的SplitChunksPlugin分包方案要如何进行配置，以得到更优的分包策略。这些配置项真复杂啊，webpack配置也成为了一项技能


## 2022.01.01

### 你应该了解的前端标准化
https://mp.weixin.qq.com/s/6zdppvbLyPz9cd8ZWGdUVA  
纪要：对前端标准化的体系进行了普及，了解标准化的历史也能更好地理解前端是如何发展的，里面提到很多延伸的知识点可以再深入了解：https://f2e.tech/home

### 快速掌握 Performance 性能分析：一个真实的优化案例
https://mp.weixin.qq.com/s/T_Z_xKByZwbrvERoG-1OFw  
纪要：通过简单案例介绍如何进行性能优化，性能优化其实没有什么银弹，也不是非常难的技术，就是找到瓶颈解决，再找到瓶颈解决的过程


## 2021.12.25

### DevTools 实现原理与性能分析实战
https://mp.weixin.qq.com/s/H8iahg5WUOHXeRzvf0R01w  
纪要：概述了网页调试工具的发展历程，chrome devtools的实现架构，其中PC端可以调试移动端的实现很有启发：通过client-server模式，用websocket封装json数据在浏览器内核间进行数据传输处理，可以实现js执行、移动端画面回显到PC端等功能

### 在政采云如何写前端技术方案文档
https://mp.weixin.qq.com/s/UYZeA3XCJzpErH5qxMRrXQ  
纪要：前端怎么写技术方案一直也是让我头疼的事，和后端相比前端变化太快，一些分层和细粒度也不是很明确，所以导致一直处于缺失状态，大家自由发挥。这篇文章实践是一份不错的参考案例，其实核心就是通过方案把问题说明白，流程图、伪代码、图例都是手段，后面可以参考实践

### 从WebGL到WebGPU，网页图形的全新时代
https://mp.weixin.qq.com/s/4LfaNHP77s9n9SghucYoaA  
纪要：介绍了WebGL到WebGPU的发展历程，WebGL已经不再发展了，不论是他的标准拥有者或是浏览器厂商都不再发展支持。开发者使用WebGL时也是在黑盒使用，性能不佳，无法发挥显卡的真正性能。而WebGPU标准是众浏览厂商角力商讨的标准，可以直接调用GPU的底层能力，图形渲染、显卡计算都能用到，可以说让web能做的事更加广泛了。这个标准还很新，真正实践落地估计还要好几年的时间，很期待广泛应用的那天，或许web上不仅仅是只是炫酷的动画，甚至一些大型游戏、大型计算都能在web上运行？

### 语雀：在线富文本编辑器的架构设计及实践
https://mp.weixin.qq.com/s/aEgAwGK568VbFi3UH-sh5A  
纪要：富文本编辑器在前端领域是一个相当复杂的技术，因为需要支持兼容各种类型的素材，而近年来数据驱动视图的思想、同时在线编辑的需求则将助推了这部分技术的发展，也衍生了不少在线协作产品。这篇分享值得学习的是编辑器的架构思想，通过分层、控制、插件的形式明确各模块职责，避免单个模块的复杂度，构建复杂工程时可学习借鉴
