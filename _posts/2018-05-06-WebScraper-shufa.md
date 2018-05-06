---
layout: post
title: "使用WebScraper从中国书法家园上爬取了一些书法比赛信息（5月6日）"
description: "使用WebScraper从中国书法家园上爬取了一些书法比赛信息."
categories: [记录]
tags: [WebScraper, 书法, 比赛, 爬虫, 爬取数据]
redirect_from:
  - /2018/05/06/
typora-root-url: ..
---

今天学会了如何使用[webscraper](http://webscraper.io)，从网站上爬取数据。在[中国书法家园](http://www.eshufa.com/)上尝试爬取了一些比赛信息（5月6日起有效信息）。现将其放在博客中，看看效果。初次涉足爬虫，觉得十分新鲜有趣。

| 截止时间   | 大赛（详情点击链接）                                         |
| ---------- | ------------------------------------------------------------ |
| 2018/05/10 | [第二届“欧阳修”杯全国少儿书画大赛征稿启事](http://www.eshufa.com/?viewnews-22230.html) |
| 2018/05/15 | [青海省第二届女性书法篆刻作品展征稿启事](http://www.eshufa.com/?viewnews-22257.html) |
| 2018/05/15 | [全国第二届大学生书法篆刻作品展征稿启事](http://www.eshufa.com/?viewnews-22244.html) |
| 2018/05/15 | [全国第二届高等书法教育论坛征稿启事](http://www.eshufa.com/?viewnews-22242.html) |
| 2018/05/20 | [河北省第九届妇女书法展征稿启事](http://www.eshufa.com/?viewnews-22289.html) |
| 2018/05/20 | [重庆市群众书法大赛征稿启事](http://www.eshufa.com/?viewnews-22265.html) |
| 2018/05/25 | [第三届“笔墨先锋”杯全国硬笔书法大赛征稿启事](http://www.eshufa.com/?viewnews-22234.html) |
| 2018/05/30 | [第八届江苏省少年儿童现场书画大赛征稿启事](http://www.eshufa.com/?viewnews-22274.html) |
| 2018/05/31 | [“诺尔科技杯”第五届山东青年临书大展征稿启事](http://www.eshufa.com/?viewnews-22267.html) |
| 2018/05/31 | [守望兰亭——福建省第四届书法篆刻展征稿启事](http://www.eshufa.com/?viewnews-22273.html) |
| 2018/05/31 | [为时代放歌——南京市纪念改革开放四十周年书法作品展征稿启事](http://www.eshufa.com/?viewnews-22247.html) |
| 2018/06/10 | [第六届安徽省篆刻艺术展征稿启事](http://www.eshufa.com/?viewnews-22293.html) |
| 2018/06/10 | [第三届全国“三笔字”书法作品评选征稿启事](http://www.eshufa.com/?viewnews-22241.html) |
| 2018/06/10 | [第四届“华夏万卷杯”全国少年书法家大赛征稿启事](http://www.eshufa.com/?viewnews-22240.html) |
| 2018/06/15 | [2018首届“米芾杯”国际青少年书法大赛征稿启事](http://www.eshufa.com/?viewnews-22258.html) |
| 2018/06/15 | [江苏省第十一届新人书法篆刻作品展征稿启事](http://www.eshufa.com/?viewnews-22255.html) |
| 2018/06/30 | [“翔龙阁杯”第三届山东青年书法（篆刻）小品展征稿启事](http://www.eshufa.com/?viewnews-22268.html) |
| 2018/06/30 | [第七届河北省硬笔书法大汇展征稿启事](http://www.eshufa.com/?viewnews-22260.html) |
| 2018/06/30 | [甘肃省第五届“张芝奖”书法大展征稿启事](http://www.eshufa.com/?viewnews-22256.html) |
| 2018/06/30 | [江苏省第二届“七彩语文杯”中小学教师正书书法比赛通知](http://www.eshufa.com/?viewnews-22280.html) |
| 2018/06/30 | [江苏省第六届刻字艺术展征稿启事](http://www.eshufa.com/?viewnews-22305.html) |
| 2018/06/30 | [辽宁省首届老年书法展征稿启事](http://www.eshufa.com/?viewnews-22295.html) |
| 2018/06/30 | [四川省第五届硬笔书法艺术展征稿启事](http://www.eshufa.com/?viewnews-22269.html) |
| 2018/07/01 | [“徽派印象”首届全国书画大赛征稿启事](http://www.eshufa.com/?viewnews-22277.html) |
| 2018/07/10 | [第八届广东省新人新作书法展征稿启事](http://www.eshufa.com/?viewnews-22272.html) |
| 2018/07/15 | [“纪念杨升庵诞辰530周年”全国书法作品展征稿启事](http://www.eshufa.com/?viewnews-22262.html) |
| 2018/07/15 | [“陆维钊奖”第八届浙江省中青年书法篆刻展征稿启事](http://www.eshufa.com/?viewnews-22287.html) |
| 2018/07/15 | [“卫夫人杯”全国妇女书法展征稿启事](http://www.eshufa.com/?viewnews-22285.html) |
| 2018/07/15 | [2018年光泽“中国生态食品城”全国书法作品展征稿启事](http://www.eshufa.com/?viewnews-22284.html) |
| 2018/07/15 | [广东省第六届“南雅奖”书法篆刻展征稿启事](http://www.eshufa.com/?viewnews-22271.html) |
| 2018/07/20 | [首届“介堪·去疾杯”全国泰顺石篆刻大赛征稿启事](http://www.eshufa.com/?viewnews-22279.html) |
| 2018/07/23 | [“醉美泸州 四方杯”第二届四川省硬笔书法大赛征稿启事](http://www.eshufa.com/?viewnews-22282.html) |
| 2018/07/25 | [第二届“弄潮杯”钱塘江全国篆刻大赛征稿启事](http://www.eshufa.com/?viewnews-22288.html) |
| 2018/07/30 | [贵州省第五届“恒安杯”篆书隶书篆刻艺术大展征稿启事](http://www.eshufa.com/?viewnews-22291.html) |
| 2018/07/31 | [“映山红”杯全国书法作品展征稿启事](http://www.eshufa.com/?viewnews-22259.html) |
| 2018/07/31 | [第二届“中国书法·中原论坛”征稿启事](http://www.eshufa.com/?viewnews-22292.html) |
| 2018/07/31 | [第三届“浙东书风”全国书法展暨三老碑小品展征稿启事](http://www.eshufa.com/?viewnews-22254.html) |
| 2018/07/31 | [第十届“观音山杯”全国书法艺术大展征稿启事](http://www.eshufa.com/?viewnews-22246.html) |
| 2018/07/31 | [第五届上海奉贤“言子杯”国际学生书法大赛征稿启事](http://www.eshufa.com/?viewnews-22290.html) |
| 2018/07/31 | [全国第三届篆书作品展征稿启事](http://www.eshufa.com/?viewnews-22296.html) |
| 2018/10/20 | [第二届“中国字 中国风”全国大书法比赛征稿启事](http://www.eshufa.com/?viewnews-22286.html) |