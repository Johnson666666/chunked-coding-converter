# Chunked coding converter

本插件主要用于分块传输绕WAF，不了解分块传输绕WAF的请阅读文末的文章。

## 插件编译

```
mvn package
```

## 插件使用

![菜单](doc/menu.png)

![配置](doc/config.png)

延时分块传输

![延时分块传输](doc/bypass-through-sleep-chunked.png)

## 相关文章
* [绕安全狗实例 + 代理sqlmap](https://www.cnblogs.com/renhaoblog/p/13395539.html)
* [编写插件者亲自写的：编写Burp分块传输插件绕WAF微信版，无编写者亲自代理sqlmap，怕博客关闭备用](https://mp.weixin.qq.com/s?__biz=Mzg3NjA4MTQ1NQ==&mid=2247483787&idx=1&sn=54c33727696f8ee6d67f997acc11ab89&chksm=cf36f9cbf84170dd7da9b48b3365fb05d7ccec6bdeff480d0c38962f712e400a40b2b38dc467&token=360242838&lang=zh_CN#rd) + [博客版：有编写者亲自代理sqlmap](https://gv7.me/articles/2019/chunked-coding-converter/)
* [酒仙桥讲解+实战：唯快不破的分块传输绕WAF](https://mp.weixin.qq.com/s/pM1ULCqNdQwSB7hcltrbtw)
* [利用分块传输吊打所有WAF](https://www.anquanke.com/post/id/169738)
* [在HTTP协议层面绕过WAF](https://www.freebuf.com/news/193659.html)
* [Java反序列化数据绕WAF之延时分块传输](https://gv7.me/articles/2021/java-deserialized-data-bypasses-waf-through-sleep-chunked/)
