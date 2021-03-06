# Python3爬虫集合
* 12306--12306爬虫  
实现了模拟登录12306和查询余票的功能.
* Avengers--复仇者联盟4评论爬虫  
实现了模拟登录豆瓣，爬取复仇者联盟4的短评内容，并进行情感分析和生成词云.
* AutoWeather--自动天气爬虫  
根据本机IP获取物理位置，然后查询天气并用语音播报.
* BaiJiaHao--百家号爬虫  
获取百度热搜事件的搜索结果中百家号所占的比例.
* Bilibili--B站直播弹幕爬虫  
多线程爬虫爬取B站比赛直播弹幕，弹幕数量七万多条，并根据弹幕内容生成词云。
* Blogs--博客园爬虫  
爬取博客园首页上的博客信息并进行分析.
* BookingSystem--新的12306爬虫  
在之前的12306爬虫基础上，更新了模拟登录的代码，实现了订购车票的功能.
* CelerySpider--基于Celery的爬虫  
基于Celery开发的爬虫，使用Redis作为中间件和结果存储，使用任务队列加速爬取.
* CRMSpider--农田数据爬虫  
模拟表单提交，使用多进程爬取农田作物数据信息.
* DianPing--大众点评爬虫  
主要破解了大众点评的SVG矢量图反爬.
* DouYu--斗鱼弹幕爬虫  
利用斗鱼的第三方接口爬取斗鱼直播间的弹幕信息和礼物情况.
* Expression--表情包爬虫  
使用生产者/消费者模式+队列大量爬取表情包图片.
* FJCourt--福建开庭公告爬虫  
合理使用GET请求和POST请求，多进程爬取福建法院开庭公告.
* JingMi--静觅博客爬虫  
使用异步协程爬取静觅博客里的博客数据并进行分析.
* KuGou--酷狗音乐爬虫  
按歌曲名称进行搜索和下载，经测试可以下载付费歌曲.
* MaoYan--猫眼电影爬虫  
主要破解了猫眼电影的字符集反爬.
* ProxyPool--IP代理池  
爬取网上的免费IP代理，然后使用Redis数据库搭建代理池，使用异步协程检测代理可用性.
* RedisCrawler--Redis分布式爬虫  
使用Redis数据库和requests库开发的分布式爬虫，并使用多进程爬取和下载图片.
* TianYa--天涯图片爬虫  
破解了天涯社区的Cookie防盗链和时间戳防盗链，下载图片分社区的图片.
* WangYiYun--网易云音乐爬虫  
破解网易云音乐的JS加密，然后反爬歌曲的评论并生成词云.
* WeRead--微信读书爬虫
多进程爬取微信读书十四万条书本信息分析什么样的书籍和作者更受欢迎.
* Weather--天气爬虫  
爬取指定城市的天气预报情况并发送邮件到指定邮箱.
* WeiBoUsers--微博用户爬虫  
模拟登录新浪微博.  
爬取微博用户的关注和粉丝数据并进行绘图分析.
