```
title: 玩转hexo # 文章标题  
date: 2023/1/22 22:00:00  # 文章发表时间
tags:

- hexo
- 美化
- 博客
  thumbnail: https://lixudongself.eu.org/hexo封面.png # 略缩图
```

## 1.添加和删除导航栏的快捷图标

<img src="C:\Users\li\AppData\Roaming\Typora\typora-user-images\image-20230122190909296.png" alt="image-20230122190909296" style="zoom:100%;" />

Miccall 主题内涵盖有常用的图标位置在`...\web1\themes\miccall\source\css`目录下`font-awesome.min.css`文件内

![image-20230122191138728](C:\Users\li\AppData\Roaming\Typora\typora-user-images\image-20230122191138728.png)

格式如上，仅需要将`onedrive`位置更换为需要的名称，图标在http://fontawesome.io/icons/#brand该网站获取

在搜索到想要的icon之后

<img src="C:\Users\li\AppData\Roaming\Typora\typora-user-images\image-20230122191530014.png" alt="image-20230122191530014" style="zoom:70%;" />

将`“f0a0”`填入`content`

接下来来到`...\web1\themes\miccall\_config.yml`

![image-20230122191720461](C:\Users\li\AppData\Roaming\Typora\typora-user-images\image-20230122191720461.png)

在已有的元素后添加刚才设定的名称 并按照格式粘贴链接即可

## 2.开始创作文章

文章目录`web1/source/_post`下新建一个`.md`文件：

```
---
title: # 文章标题  
date: 2017/3/27 13:48:25  # 文章发表时间
tags:
- 标签1
- 标签2 (可选)
categories: Algorithm # 分类
thumbnail: https://xxxxxxxxxx.png # 略缩图
---

文章正文
```

