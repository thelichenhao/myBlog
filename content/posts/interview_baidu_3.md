---
title: "百度开发一面"
date: 2023-06-07T00:44:13-04:00
# weight: 1
# aliases: ["/first"]
tags: ["百度", "面试", "开发"]
author: "Me"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "The first interview of Baidu SDE."
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/thelichenhao/myBlog/tree/main/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---


## 流程

- 自我介绍
- 讲了一个项目，以及项目中遇到的问题，如何解决的，项目能解决哪些实际问题等
- 问了一些C++的知识
  - STL的容器，比如vector和list的区别，map和unordered_map的区别，以及map的底层实现等。
  - 多态的机制，问到了虚函数表
- 算法题：给定一个正整数N，每次操作可以加上或者减去2的幂次，问最少几次得到0。比如N=10，可以先加上2^3，再减去2^3，再减去2^1，就可以得到0，所以答案是3。
  - 从低位往高位遍历，遇到连续的1时就进位，遇到单个1就直接减去即可。

## 总结

面的部门是推荐系统架构，面试官是我见过的最耐心的了，我不会的问题也会给提示，最后的算法题也一直引导。最后还提醒我注意一下国内电话打不通的问题，真的是非常nice了。希望能够有机会二面吧。