
[Juude](https://github.com/Juude) 的 2014 -> 2015
-------------
本来自己唧唧歪歪惯了，也是打算写个2014小结的，既然特雷娜等人在这玩的很嗨，我也来凑凑热闹吧。年纪大了，话就会多点，请原谅我一生不羁放纵爱啰嗦～～  
##开始
想起2014年刚开始的时候，我也像现在这样回首过去，展望未来。当时觉得自己的不足有  
1. 虽然做了很多事情，但是缺少深度的思考。  
2. 基础知识不够扎实。  

还有一个希望是： 做一款自己的的app。  

所以自己的2014年目标是:  
1. 写30篇博客，可以让我更深度思考  
2. 重新学习算法 操作系统等基础知识  
3. 做一款自己的app并且上架  

###乐蛙
####开源的热情: x2ools
因为经常玩xposed，之前也写了一些xposed应用以加强调试功能，加上自己玩的应用也很多，所以就想到了用xposed写一个快速查找应用的[X2ools]( https://github.com/X2ools/X2ools)
，第一版很快就完成了，给周围的一些朋友看，反响还不错，于是拉了[bjzhou](https://github.com/bjzhou)一起来开发，并且建立了组织[x2ools](https://github.com/X2ools)。之后我对产品这一块也开始感兴趣，想了许多新功能，而bjzhou实现的也很快，所以最终还是实现了不少功能的。然而俩人对设计都没经验，且只愿意做自己感兴趣的功能。当兴趣淡了的时候也就不再更新了。以至于当某位仁兄在未告知我们的时候把我们的项目直接换了几张图而在app市场上架，我们俩竟然都几乎无动于衷。之后又做了[droidMocks](https://github.com/Juude/droidMocks), 是一个模拟数据，以及运行时调试的Android 开发框架。没有做太大宣传，不过自己用在几个app里，对应用开发效率提高不少。  

####博客
之前就一直写博客，然而大多数是写给自己看的，抒发下伤春怀秋之情倒可，真正却产生不了价值。这种文字，一天写几篇都可以，深度的思考却有限。但是当写博客是为了给别人看的时候，就有了责任要把事情写得清楚而且正确。以这种心态，才发现写一篇自己满意的有多困难。最终我写了十篇左右，令自己满意得不多，不过我的一些朋友读起来给的评价还不错，翻译的[为何google并不青睐招聘名校毕业生](http://juuda.com/?p=233)也被不少网站无节操地转载。然而写博客最大的好处是让我养成了深度思考的习惯。对自己的想法会进行审视，对别人的观点也会质疑。即使因此让某些朋友觉得不够信任他，我仍相信这是更正确的思考方式。  

####跳槽
四五月的时候，我开始想着跳槽。究其原因，一是身边一起战斗过的大神们都已经走了，剩下的人已经不能让我快速的成长。netflix认为对一个员工最好的福利就是好的工作伙伴，这也是我想跳槽最大的原因。二是付出与回报不成正比，这包括影响力与待遇上。细节也不便多说。最终决定进入了OPPO，原因是1. 面试的时候觉得面试官的技术能力不错2. OPPO的产品我觉得不错。  

###在OPPO的折腾
在OPPO只做了两件事情： 性能优化和最近任务重构
####性能优化
OPPO对质量要求很高，每件事情都要求做到极致，所以让我在乐蛙那样做那么多模块是不可能的。所幸性能优化是我之前一直很感兴趣的东西，这个时候正好可以深度研究。这段时间，把traceview systrace用得很熟。并且研究了下surfaceflinger以及hwui，skia相关偏底层的内容。最终感觉是学了很多东西，产生的效益却不大，我在几个月内性能方面的改动只有几次提交，其中有几次还在另一方面降低了性能被撤回了。深深体会到了“过早优化是万恶之源这句话”。

####最近任务重构
通过最近任务重构学习了RecyclerView的构造。刚接触时候还没有RecyclerView还没有发布,但是当时对于新技术太过痴迷，所以还是选择了preview版本的RecyclerView，做了太多的定制，也对View系统了解的更深刻。最重要的是看到了RecyclerView优化的过程，而不是结果，这也是很不错的体验。  

####其他事情
这时候对数据分析感兴趣，打算用umeng收集一些个人信息。所以就有了项目[SelfTracker](https://github.com/Juude/SelfTracker),目前只是实现了记录每天记录自己开了几次手机，每次用手机多长时间。后来打算自己写服务器，用web.py 写了几个demo，不过记不清因为什么事情耽误了，后来也就无疾而终。为了学习算法，重新拾起编程珠玑，用python实现了一些算法，在leetcode上做了几个题目。学习了下SCIP这本书，经常被里面很有洞察性的话触动，同时感叹下自己的渺小。  

###到新公司
OPPO是一个不错的公司，但是我还是离开了。因为之前的几个来深圳的小伙伴都因为都回了上海，而我一个人在这里显得了无所依。而且因为交际圈还是在上海。仔细考虑后，还是回了上海。这次是因为bjzhou遇到了jiaqing同学，谈了谈后，很戏剧性地就到了新的公司:葡萄一族。  

这里待得时间还不长。接触了一些wayland skia hwui的东西，研究了下xmqq mtqq的协议，以及做了些推送和IM的demo。因为刚成立不久，产品尚未定义好，也兼职了下产品的工作，从产品理念到开发流程，算是额外的奖励吧。然后帮hr姐姐找了些人，通过找人发现：  
- 熟人介绍最靠谱  
- 猎头还算靠谱  
- 51job等的简历质量太差   
- 通过github或博客找人适合长期的，短期找人不适合  
（这里打个小广告：我们公司 葡萄一族是做软硬件结合的创业公司，妹子多，前途大  iOS android H5 php长期招人，有志青年发送邮件到juude.song@gmail.com 帮内推 ～～～
）  

###生活方面  
遇到了漂亮的妹子，不断让我惊喜得发现这世界居然比我想象得还要美好，然而自己犹豫不决，既猥且琐，实在是2B地很。
上半年练习了羽毛球，力量练习，拳击，游泳等，身体保持的不错。下半年到深圳后就放弃了，所以现在身体就不是很好了。  

###总结
1. 既然自己做不感兴趣的事情效率如此低下，尽量选择自己感兴趣的事情。  
2. 勇敢追求自己想要的东西，不断地延迟选择，就是在选择放弃。  
3. 要抛开外力作出自己的选择，不能被别人的期望而左右。  

###2015之展望  
####事业上
一是提高系统设计能力  
主要是对已经有的系统的分析，比如android view系统和recyclerview,以及自己想做但没有时间做的,比如push系统。  
二是增强基础知识  
继续阅读scip，继续练习算法题。  
三是多参加开源项目，线下沙龙，提高自己的社交圈。  
四是接触下服务器开发，iOS等拓宽知识面。  
##生活上
感情上没太多要求，虽然总是被家里催婚，然而强求未必靠谱。经营好与周围人的关系，已经足够。  
继续锻炼身体，最好有更好玩的锻炼方式，比如合气道之类的。  

> 原文也同时在[自己的博客 juuda.com](http://juuda.com/) 发布。