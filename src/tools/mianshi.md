### 自我介绍

你好面试官，我叫冯建东，是18届的毕业生，毕业学校是景德镇陶瓷大学，专业是计算机科学与技术，从事前端开发已经四年了。从刚毕业学习使用UI框架bootstrap，后面在又根据项目学习了vue，react，微信小程序。我现在对技术包含热情，编码就像解数学题一样，很有成就感。前端从刚开始的div+css，到jquery，然后到angular，再到react，vue，app，小程序，发展也是相当迅速，未来可视化也会是一个重要的分支。我也有保持学习，与时俱进。

难点：
组件：图片查看器，导航tab，评论组件，github授权登录，跟据分类来处理数据，数据库存放分类的外健，前台样式纯封装，使用变量定义好各个文字的大小，主题颜色，各个边距，封装一个资源中间键，一个接口可以让请求到多种数据，数据库id自增，瀑布流，

问题：

1. 入职需要慢一年才有5天吗
2. 我30号需要提供什么材料给你
3. 我还可以不选您这边是吗
4. 背调你需要花多久
5. 您那边有没有前端的负责人，还是就我们自己做

遗漏的一些问题
1. 你的代码怎么做规范的
2. 自动化测试
3. 怎么review代码
4. react事件，原生事件什么区别
5. 怎么判断是否登录，session，cookie
6. 路由三种模式

性能优化
链接
vue diff vs react diff
- 都是两组虚拟dom的对比(react16.8之后是fiber与虚拟dom的对比)
- 只对同级节点进行对比，简化了算法复杂度
- 都用key做为唯一标识，进行查找，只有key和标签类型相同时才会复用老节点
- 遍历前都会根据老的节点构建一个map，方便根据key快速查找
不同点
- react在diff遍历的时候，只对需要修改的节点进行了记录，形成effect list，最后才会根据effect list 进行真实dom的修改，修改时先删除，然后更新与移动，最后插入
- vue 在遍历的时候就用真实dominsertBefore方法，修改了真实dom，最后做的删除操作
- react 采用单指针从左向右进行遍历
- vue采用双指针，从两头向中间进行遍历
- react的虚拟diff比较简单，vue中做了一些优化处理，相对复杂，但效率更高

1. 图形化 ， gis, d3, three.js..
2. 移动端 ， uniapp,electron,flutter, RN..
3. 智能化方向 ， 低代码 ， ChatGPT..
4. 更好的交互方向 ， 元宇宙 ， web3.O..
5. 复杂业务解决方案方向 ， 微前端 ， 分布式的内容 （ 网页 ） 分发