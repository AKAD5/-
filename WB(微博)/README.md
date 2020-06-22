# 获取微博公共数据

## 采集数据源
  + 微博网页端 https://weibo.com/
    优点：内容丰富，缺点：结构负责
  + 微博移动端 https://m.weibo.cn/
    优点：结构相对几点，缺点：内容较少
  + 微博手机端 https://weibo.cn/
    优点：机构最为简单，缺点：内容最少
    
## 探索 
  +结合各个数据源的特点，我们选择从微博移动端进行数据采集，（直接上干货）
  +个人做数据采集的时候最先关注的就是个请求URL的变化，从中就行发现我们需要的数据，比如：
    ++ 个人主页：https://m.weibo.cn/profile/2803301701，https://m.weibo.cn/u/2803301701
    
    ++ 个人关注：https://m.weibo.cn/p/index?containerid=231051_-_followers_-_2803301701
    
    ++ 个人粉丝：https://m.weibo.cn/p/index?containerid=231051_-_fans_-_2803301701
    
    ++ 个人全部微博：https://m.weibo.cn/p/2304132803301701_-_WEIBO_SECOND_PROFILE_WEIBO
