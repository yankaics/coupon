# coupon
这是一个还在进行中的项目。

# 目标
做一个个性化的促销信息的推荐系统。

# 进度
1.爬虫部分的core。√  
2.smzdm网站首页和评论的抓取。√  
3.使用jdk的httpServer提供服务。√  
4.~~建立web端项目，收集用户log。~~ (使用不便)  
5.开发了一个[chrome插件](https://github.com/dpy1123/CouponRecorder)，记录用户在浏览smzdm时的动作。√  
6.使用weka进行后续的数据处理：  
按照view buy normal dislike分类，数据集不平衡，使用smote或cost-sensitive的方法感觉效果都不是很好；  
暂时按照view buy dislike分类。  

# TODO
1.sysout用log替换掉，否则影响性能。  
2.增加schedule定时执行。