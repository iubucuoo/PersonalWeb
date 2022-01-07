---
weight: 1
title: "测试内容-置顶第一篇"
description: "测试页面，添加新功能的时候测试用"
date: 2021-08-12T19:25:21+08:00
draft: false

resources:
- name: "featured-image"
  src: "featured-image.jpg"
---
<!--more-->
## 添加音乐
{{< music url="/music/jaychoucpns.flac" name=超跑女神 artist=周杰伦 cover="/images/jintanhao.jpg" >}}
<!---
```markdown
{{</* music url="/music/xxx.flac" name=xxx artist=xxx cover="/images/xxx.jpg" */>}}
```
--->
## 添加本地视频
{{< video id="a" url="economicprinciples.mp4" >}}
<!---
```markdown
{{< video id="a" url="/videos/testvideo.mp4" sub="" >}}
```
--->
-------------------------
### 美国Billboard榜
<!--美国Billboard榜-->
<!--{{< music auto="https://music.163.com/#/playlist?id=60198" >}}-->
{{< music auto="https://music.163.com/#/playlist?id=60198" list-folded=true >}}

---------------------------------
### 周杰伦快歌
<!--周杰伦快歌-->
{{< music auto="https://music.163.com/#/playlist?id=5332707927" list-folded=true >}}

-------------------------
### 周杰伦所有的歌
<!--周杰伦所有的歌-->
{{< music auto="https://music.163.com/#/playlist?id=402353632" list-folded=true >}}

------------------------------------------
<!--测试本地视频-->
<!--<video id="video" controls="" preload="none" poster="featured-image.jpg">
      <source id="mp4" src="economicprinciples.mp4" type="video/mp4">
</video>-->

-------------------

<!--
0
<video width="320" height="240" controls>
    <source src="movie1.mp4" type="video/mp4">
</video>
-------------------------
1

<video src="/movie/movie1.mp4" controls="controls" width="500" height="300"></video>

-----------------
2


<video width="500" height="250" controls="controls">
<source src="/movie/movie1.mp4" type="video/mp4">
</video>

----------------------------------
3

<video width="720" height="303" controls>
<source src="https://movie.cy798.cn/%E9%BB%91%E8%B1%B9.Black.Panther.2018.BD720P.X264.AAC.English.CHS-ENG.mp4" type="video/mp4">
</video>

-------------------------------------
4

<video src="https://movie.cy798.cn/Blue.Planet.S02.2017.BluRay.1080p.DTS-HD.MA5.1.2Audio.x264-CHD/Blue.Planet.S02E01.One.Ocean.2017.BluRay.1080p.DTS-HD.MA5.1.2Audio.x264-CHD.mkv" controls="controls" width="720" height="405"></video>
-->

## 添加bilibili视频

{{< bilibili BV1NM4y1g71r >}}
<!---
```markdown
{{</* bilibili xxx */>}}
```
--->
