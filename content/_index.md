---
title: 首页
date: 2022-05-14T20:01:02+08:00
---

# 韩文弢的个人主页 {#header}

![](hanwentao.png){#avatar}

我是

* [一个 []{#ethan-age} 岁男孩](https://hanyicheng.net)的爸爸
* [计算机专业的大学教师](https://www.cs.tsinghua.edu.cn/info/1114/3524.htm)
* [PACMAN 组](https://pacman.cs.tsinghua.edu.cn)曾经的小神童
* [信息学竞赛](https://noi.cn)的深度参与者
* 被社工耽误的[码农](https://github.com/hanwentao)
* 因为没人想当而赶鸭子上架又乐此不疲的[足球守门员](https://en.wikipedia.org/wiki/Goalkeeper_(association_football))
* 时断时续的[乐高](https://www.lego.com/zh-cn)玩家
* 买了还没开始学又很想成为的[唢呐](https://en.wikipedia.org/wiki/Suona)乐手

## 个人创作

* [《论 C++ 语言在信息学竞赛中的应用》](cpp-in-oi/)：本人参加 2004 年信息学国家集训队时撰写的论文
* [html2csv](https://github.com/hanwentao/html2csv)：一个将 HTML 表格转换成 CSV 格式的命令行小工具
* [tornado-webhook](https://github.com/hanwentao/tornado-webhook)：用 [Tornado](https://www.tornadoweb.org/) 实现的[网络钩子 (webhook)](https://docs.github.com/en/developers/webhooks-and-events/webhooks/about-webhooks) 服务端
* macOS 动态壁纸：[2022 北京冬奥会 24 节气](24SolarTerms.heic)、[自制简约版 12 时辰](12EarthlyBranches.heic)

## 软件推荐

* [Pandoc](https://pandoc.org/)：文档格式转换工具
* [bookdown](https://bookdown.org/)：使用 [R Markdown](https://rmarkdown.rstudio.com/) 格式写书的工具
* [GoAccess](https://goaccess.io/)：生成网站访问统计信息的工具
  * [GoAccess 1.4, a detailed tutorial](https://arnaudr.io/2020/08/10/goaccess-14-a-detailed-tutorial/)
  * [如何在 Nginx 下配置 GoAccess 的 WebSocket 功能](https://blog.51cto.com/u_1986371/2456422)
* [OBS Studio](https://obsproject.com/)：录屏、推流工具
* [BlackHole](https://existential.audio/blackhole/)：音频路由工具
* [Equinox](https://equinoxmac.com/)：macOS 动态壁纸制作工具
  * 另有命令行工具 [wallpapper](https://github.com/mczachurski/wallpapper)

## Just for Fun

* [GitHub R&eacute;sum&eacute;](https://resume.github.io/?hanwentao)

<script>
  function computeAge(year, month, day) {
    var now = new Date();
    var thisYear = now.getFullYear();
    var age = thisYear - year;
    var birthday = new Date(thisYear, month - 1, day);
    return now >= birthday ? age : age - 1;
  }
  document.getElementById("ethan-age").innerText = computeAge(2015, 7, 17);
</script>
