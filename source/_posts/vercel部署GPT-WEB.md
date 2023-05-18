---
title: 一分钟搭建部署ChatGPT国内镜像
cover: 'https://ypyobj.zkheo.top/202305182023992.png'
recommend: true
categories:
  - 教程
tags:
  - gpt
keywords:
  - gpt
  - chatgpt
  - openai
  - 搭建chatgpt
  - 部署chatgpt
abbrlink: '13e7'
date: 2023-05-18 20:20:40
---

### 前置准备

> 网络：能够访问GitHub、Vercel

- [GitHub](https://github.com/)账号
- [Vercel](https://vercel.com/)账号
- [ChatGPT-Next-Web](https://github.com/Yidadaa/ChatGPT-Next-Web)源码仓库

## 开始搭建部署

> 打开[ChatGPT-Next-Web](https://github.com/Yidadaa/ChatGPT-Next-Web)源码仓库地址，点击一键部署按钮

![image-20230518203301003](https://ypyobj.zkheo.top/image-20230518203301003.png)

> 点击`Deploy`按钮后将自动跳转到`Vercel`，点击`Create`按钮，将项目`fork`到自己的`GitHub`仓库

![image-20230518203348986](https://ypyobj.zkheo.top/image-20230518203348986.png)

> 点击`Create`按钮后，页面将会自动滑动到环境变量位置

![image-20230518203731597](https://ypyobj.zkheo.top/image-20230518203731597.png)

#### 环境变量

- OPENAI_API_KEY：OpenAI Key，用来调用官方API使用（必填），可以自行注册或搜索免费共享的KEY
  - [OpenAI账号注册教程](https://b.zkheo.top/p/d613.html)
  - [OpenAI Key免费分享](https://b.zkheo.top/p/ab52.html)
- CODE：用来分享给别人使用，屏蔽了OpenAI Key，可以配置多个，多个使用逗号来分割

> 配置完环境变量后，点击`Deploy`开始部署，部署耗时3分钟左右

![image-20230518205323244](https://ypyobj.zkheo.top/image-20230518205323244.png)

> 部署完成后将自动跳转到完成页。到此我们就算大功告成了！

> 点击右上角`Continue to Dashboard`前往控制台

![image-20230518205631982](https://ypyobj.zkheo.top/image-20230518205631982.png)

> 点击`Vercel`免费提供的域名，就可以跳转到你的站点了

![image-20230518205804037](https://ypyobj.zkheo.top/image-20230518205804037.png)

> 点击`设置`前往设置页面，填写上环境变量中配置的`CODE`或`OpenAI Key`就可以正常使用了

![image-20230518210041368](https://ypyobj.zkheo.top/image-20230518210041368.png)

![image-20230518210248565](https://ypyobj.zkheo.top/image-20230518210248565.png)

> 虽然已搭建完成，但`Vercel`提供的域名需要魔法才可以访问，如果需要国内直接访问的话还需要配置一个国内域名

## 最后

关注我的公众号：`HEO网络`

加入QQ交流群：`722807877`

收藏博客！打赏作者↓↓↓
