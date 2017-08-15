




---
## 基本信息
- 昵称：EmptyWalker            
- Email：emptywalker@163.com 
- 毕业院校：池州学院（2015/5）
- 学历：本科
- 电话：18226987542
- [微博@EmptyWalker](http://weibo.com/2607816371/profile?rightmod=1&wvr=6&mod=personinfo)、[Twitter@EmptyWalker](https://twitter.com/EmptyWalkMan)
- [Github]( https://github.com/emptywalker )、 [简书](http://www.jianshu.com/users/14857ca34ed8/latest_articles)、 [博客](https://emptywalker.github.io)


---

## 项目经历
### 2017-01 ~ 至今 (浙江蓝麦电子商务股份有限公司)
   

- 使用[WEEX](https://github.com/apache/incubator-weex)重构[土冒](https://itunes.apple.com/us/app/土冒-最挑剔的特产选品师/id965720144?mt=8)APP，并和团队一起最终完成Android、iOS、H5的三端公用，移动端都已上线。效果：在移动客户端，可以通过下发js文件的形式，实现热更新，省去了应用市场的审核过程，极大的提高了开发效率，降低了开发成本。
- 在Weex化的过程中，我主要负责：

	- Weex层面的开发，通过webpack管理项目，完成原客户端90%以上的页面开发，通过与native的提供的module/component相结合，完成拍照、获取相册图片、第三方登录、支付、分享、控制页面跳转、实例传值、webView交互等内容，完成对Android端UI的适配；
	- iOS端处理所有自定义组件、模块、全局事件的实现、对js文件的更新缓存等；
	
	- 在开发过程中，为了更大增加兼容性(.we的文件在H5会有兼容性问题)，我们完成了从.we文件过渡到.vue文件。在这个过程中，除了使用官方的工具进行了转换，还自己添加一些特定的修改。对.vue中弃用的两个功能进行了手动替换：
		- dispatch组件传值手动换成@method=method形式的传值方式；
		- BroadcastChannel替换成GlobalEvent进行实例传值，在iOS和Android实现这个功能都需要原生的支持，并且对官方提供的方法进行了修改。为此我还写了[一篇文章](http://www.jianshu.com/p/d17b83c1f873)关于这个过程在iOS的实现；
		- 对Android做适配。
	- 活跃于[weex中文社区](https://segmentfault.com/t/weex)，目前标签下[声望排名第三](https://segmentfault.com/u/xlihey)。
		

### 2016-06 ~ 2017-01 (浙江蓝麦电子商务股份有限公司)
- 接触前端开发，了解一下Html、CSS、JavaScript，完成公司[手机主页](htts://www.toomao.com)的开发。
- weex开源了，开始研究weex的框架，从playground入手对每个组件进行学习尝试，并在之后将手机主页使用weex开发从新上线。这是第一次尝试weex的实战场景。在经过一段时间的深入学习之后，发现weex具有满足我们现有APP开发的技术条件后，着手准备将现有APP转成weex，从而达到降低开发成本，提高开发效率的目的
- 维护iOS端的更新与日常开发

### 2015-05 ~ 2016-06 (浙江蓝麦电子商务股份有限公司)

- 从0-1搭建土冒iOS客户端，根据业务模块对项目进行基本的构建，模块内部采用MVC的设计模式，引入cocoapods对第三方库进行依赖管理，对相关第三方进行第二层封装，有效避免了第三方api变更带来的巨大灾难，写好用户数据缓存类、导航的设置、网络请求；

- 在中期开发人员增多的情况下，和团队一起制定编码规范，项目框架的修改。探索常见的crash类型和调试方法，如：
	- EXC_CRASH unrecognized selector 采用 All Exception Point
	- SIGSEGV、 EXC_BAD_ACCESS 采用 NSZombie
	- SIGABRT 出现次数比较少，通过代码的逻辑检查
	
- 在团队中愿意接受挑战，去完成一些有难度的任务，如：接受购物车、确认订单、支付、店铺详情、商家管理等模块的开发；

- 帮助团队解决一些偶发性错误。比如：由于tabbleView的cellForRowAtIndexPath的异步调用，在一些数据经常变化的页面中，会偶尔出现数组越界，因此对这样的数组在每次获取值得时候进行安全检查，必要时采用线程安全组数。
- 使用instruments对项目进行检测，及时发现一写内存泄漏、野指针、耗时的操作

---

## 我的技能：
- Objective-C
	- 比较了解GCD、NSOperation的基本思想和使用
	- 了解runtime的基本知识，其动态化过程，并使用runtime实现过项目中的AOP埋点
	- 对面向协议和工厂模式有基本的理解和使用，对设计模式看法是：适合当前业务的就是最好的
	- 阅读过AFNetWorking、weex的部分源码


-  H5 + WEEX + Vue
	- 对web的html、CSS、JavaScript，基本了解，并能够实际运用，使用H5开发过公司的[手机主页](https://www.toomao.com)
	- 熟悉使用weex进行项目开发。已经上线纯weex的商业级项目 土冒APP。对weex的使用态度：建议局部动态页面使用weex来替换webViwe，从而增强交互体验。全部使用weex在Android上回出现很大性能问题：OOM、卡顿。
	- 因为weex的开发需要，对Vue有一些入门的了解

- Swift
	- 学习完了《The Swift Programming Language》3.0.1版本内容，基本完成了swift3.0的入门,并且关注swift的动态,多次参与Swift GG线下沙龙，拥抱RxSwift.
- 英语(CET-4),习惯于google、stackoverflow、raywenderlick、自带梯子；阅读过《iOS Apprentice》部分章节的英文书籍， 




## 作品展示和开源项目
### 作品展示
- [土冒](https://itunes.apple.com/cn/app/tu-mao-jin-kou-ling-shi-%20gou/id965720144?mt=8)
- [土冒手机web主页](https://www.toomao.com) 手机端H5
- [GitHub](https://github.com/emptywalker)

### 开源项目
 - [weex 实现一个采购系统](https://github.com/emptywalker/PurchasingPlatform)  局部功能
 - 对weex项目提交过关于导航控制器的[PR](https://github.com/apache/incubator-weex/pull/267)
 
---

## 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。


