




---
## 基本信息

 姓名：  | Email： | 电话：|
| :------:| :------: | :------: | :------: |  :------: |
| 许有红| emptywalker@163.com | 18226987542 | 池州学院（2015-05） |  本科 |

 毕业院校：  | 毕业时间： | 学历：| 其它 |
| :------:| :------: | :------: | :-----: |
| 池州学院| 2015-05 | 本科 | [Github]( https://github.com/emptywalker )、[博客](https://emptywalker.github.io)、 [简书](http://www.jianshu.com/users/14857ca34ed8/latest_articles) |

---

## 项目经历
### 2015-05 ~ 2017-09 (浙江蓝麦电子商务股份有限公司)
主要完成一个电商平台的[ APP 土冒](https://itunes.apple.com/cn/app/tu-mao-yi-ge-te-chan-yi-ge-gu-shi/id965720144)，其主涉及的业务模块是首页、分类、商品列表展示、活动商品展示、商品详情、购物车、确认订单、会员、券管理、支付、订单管理、退款处理、退款纠纷处理、物流显示、订单评价等。 iOS 的同事从 1-4-1。从个人技术发展角度，我的工作分为以下两个阶段：

**2016-12 之前**

- 上线 土冒 APP，完成前两个版本的迭代，搭建基础架构。
- 然后和新的小伙伴一起完成 APP 的架构调整，使其完全遵循 MVC 模式。并独立封装了网络库、缓存机制、JSON 到 Objective-C 对象的转换、颜色分类、字符处理、利用 CocoaPods 管理第三方依赖等；并一起制定代码规范，并形成文档，包括项目的新手教程。
- 优化 TableView 滑动卡顿的问题，寻找减少卡顿的主要方式： cell 的高度预计算，减少 cell 布局更新，减少 Image 的离屏渲染。

**2016-12 ~ 2017-09**
- 随着 [Weex](https://github.com/apache/incubator-weex) 的内测开始，我开始学习 Weex，以公司的已有业务作为 Demo 去学习，探索 Weex 在项目中能否提供有效的价值。经过多个页面研究之后，在 Weex 宣布开源之后，开始在线上实现了一个简单的业务页面，并能满足线上需求。
- 第二阶段，开始着手多页面，和对需要动态页面( H5 )进行替换。对 Weex 基础模块和组件进行搭建，比如:对 storage 增加同步取值的方法，硬件的能力获取（拍照、三方登录、分享、支付等）， Android 里由于图片造成的 OOM 进行优化，BundleJs 的更新缓存机制的搭建等。
- 第三阶段，全部使用 Weex 翻写整个 APP，这一过程中，由于将 Weex 原本的 `.we` 转成 `.vue` 的过程中出现了一些问题，[总结在这里](https://www.jianshu.com/p/d17b83c1f873)。
- 在 Weex 学习的过程，活跃于[ Weex 中文社区](https://segmentfault.com/t/weex)，目前标签下[声望排名第四](https://segmentfault.com/u/xlihey)；积极参与 WeexConf；并给 Weex 仓库提交过多个 [PR](https://github.com/apache/incubator-weex/commits?author=emptywalker)。
		

### 2017-09 ~ 2017-12 (杭州云若网络科技有限公司)
从事[达人店 APP](https://itunes.apple.com/cn/app/id1123389168) 的开发维护。主要也是基于 Weex 完成多端的开发，大致工作内容如下：
- 清理当前项目的废弃代码，使文件结构更加清晰，总结 git 分支管理规范，新手教程等文档；
- 在现在 Weex 架构基础上，增加可以多个页面同时调试，极大的提高了页面联调的效率；
- 实现了一个基础版本的埋点机制，利用 runtime hook 按钮的点击事件，并生成一个特定的数据结构(包含设备平台信息、网络状态、事件名称、来源)，完成数据收集，在 APP 进入前台或者进入后台的时候上传收集的点击事件，也可以对特定事件进行收集。
- 开朗的性格给团队带来不少活力，多次主持周会加强了同事之间的友谊，有利于后续工作的高效合作。

### 2017-12 ~ 至今 (杭州米雅信息科技有限公司)
我从事公司 ToB 端[米雅支持 APP ](https://itunes.apple.com/cn/app/%E7%B1%B3%E9%9B%85%E6%94%AF%E6%8C%81/id1341532078?mt=8) 的开发。该产品主要是通过对交易数据的各种维度分析( GMV、客单价、交易笔数、新老顾客、支付通道、客层等)，配合丰富的图表(折线图、柱状图、饼图)向客户和公司内部展示数据，从而达到直观的了解交易走势和问题分析。我主要从事的工作如下：
- 利用 Weex 快速搭建一个跨平台项目，完成 iOS 和 Android 上米雅支持 APP 的快速上线；
- 寻找适合跨端的图表框架，一开始选择，由 native 提供图表组件给 WEEX 使用，后期发现 native 提供的组件丰富性不足，和维护成本太高；后来，就寻找替换方案，使用了 echarts + webView 的形式来展示图表。主要的思想是将 echarts 和适配好的 html 文件利用 webpack 进行编译打包，然后缓存到本地，在 APP 里直接加载本地的 html 并结合对应的参数进行展示。

## 我的技能：
 Objective-C | H5 + Weex + Vue | Swift |
| :------| ------: | :------: |




## 作品展示和开源项目
### 作品展示
 [土冒](https://itunes.apple.com/cn/app/tu-mao-jin-kou-ling-shi-%20gou/id965720144?mt=8) | [土冒手机web主页](https://www.toomao.com) | [GitHub](https://github.com/emptywalker) |
| :------| ------: | :------: |


### 参与开源项目
 - [Weex](https://github.com/apache/incubator-weex/commits?author=emptywalker)
 
---

## 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。


