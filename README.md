Batman自动化测试框架开发计划
============================

#### Batman是一个开源的web前端测试框架, 基于watir引擎, 主要用来测试基于IE的web应用.
___________________________________________________________
#### 设计逻辑  

> 功能集中而实用  
> 框架轻量 扩展重量  
> 方便调试开发   

### 开发公告
##### 1 优化初始化部分的代码--未完成  

    > 目前测试开始的初始化部分的代码不是很统一.  
    > 件等初始化的时间戳是各自生成的, 在后续阅读的时候也很多麻烦.  
    > 所以准备重构这部分的代码 统一生成时间戳以及文件名等.  

##### 2 优化重构测试日志和控制台输出的代码--未完成  
    > 目前的问题在于控制台输出的信息不能完全的收集统计.  
    > 计划是准备将测试日志和控制台输出区分开 工作量比较大...  
    > 再就是重启$DEBUG_LEVEL这个机制, 具体的方法还在设计中  

##### 3 加入单个case的调试功能--未完成  
    > 很简单, 主要就是加入单个case的调试功能  
    > 计划在config中加入单个case调试的开关, 开启后编译单个case就可以执行当前用例.  
    > 还要修改当前的case结构, 也在设计一个合理的方式方法  

##### 4 加入测试计划机制--未完成  

    > 允许用户按照指定的顺序运行指定的case  
    > 初步设计会在plan文件夹中加入一个test_plan.rb文件, 用来存储执行队列.  
    > 会写一个工具用来生成测试计划, 基本思路已经想好了, 一定让大家觉得舒服.^__^     

##### 暂时就这些, 写完了我会标注  
___________________________________________________________
#### 远期计划  
1. 优化异常处理机制  
2. 优化测试报告  
3. 优化测试日志数据库的功能  
4. 创建报表功能   
5. 好多好多...  
___________________________________________________________
- Author: wangpc
- Weibo: [@王小毛][wang_weibo]
- Mail: wangpc.mobile@gmail.com
[wang_weibo]: http://weibo.com/hexogen 

