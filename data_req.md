## 虫 子 计 划 ##
　　　　　　　　

1. 实现功能
 爬互联网上人家刚发布的微信群二维码,且自动加入这些群中!


2. 先以一些简单的网站为入口 如互动吧与http://www.weixinqun.com 为demo 

3. 爬虫的架构一定要有可移植性

  * 即可以趴这个网站也可以爬虫那个网站,基本就是不用改什么代码,配置一就就可以随意处理任意网站
  * 可以应对不同关键词的处理.
  * 并不是所有的图片都是二维码，so这个如何解决？
  
4. 以上三点实现了，那么就可以扫描任意网站的二维码了。
 * 咱们就在ubuntu server上以腾讯的所有微信公众号为入口，定时扫描这些公众号发出来的二维码。



4. 金融數據：投资人联系方式

5. 茶行业数据

6. 家医群数据

7. many wechat accounts（一台linux多开wechat帐户?，虚拟机方案） auto add friends
 * add friends from excel file friends.xls
 * add message as "hi 王鞠华 您好，xxx"
 * Linux version: wechat https://github.com/geeeeeeeeek/electronic-wechat 
 * Limit QQ have limit the NO. of friends which we plan to add everyday.
