---
title: Analysis of P2P network data distribution technonlgy
copyright: true
top: 1
categories:
- Technonlgy
- Code
tags:
- Science
- Mathematics
- Power Electonics
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## P2P原理分析说明
reference:
[知乎](https://www.zhihu.com/question/24884045)
[CSDN](https://blog.csdn.net/dog250/article/details/46839201)
### P2P 通俗解释
<<葵花宝典》，全背下来要2个时辰，我和师兄潜入书房得到一套上下册但无法带出，每个人自己管自己背，要4个时辰后才能逃离书房。且以后互相不交流秘籍内容。新来的人还是要去书房偷看。如果我背上册，师兄背下册，我们1个时辰就能悄悄离开书房。回家后再花2个时辰互相交流上下册补全即可。共计3个时辰。而且只在书房里呆了1个时辰，被发现的概率大大降低。遇到新来的人，不需要去书房，我们直接讲给他听即可。
### 数学模型与分析
典型的P2P网络是一个全互联的网络，意思是每一对节点间都有一个双向连接，但是实际上，这个连接是逻辑上的，并非物理连接，在当前的互联网上，它指的是TCP/IP的网络连通性，而不是指实际存在全互联的网线，那样的话，世界真的成了19世纪末电话线那样的蜘蛛网了
### new world new time

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```
ewfwfew

More info: [Server](https://hexo.io/docs/server.html)

<!--more-->

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)

fewew

```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
