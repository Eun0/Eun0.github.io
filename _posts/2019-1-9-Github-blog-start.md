---
layout : post
title : kiko-now 지킬 테마로 Github 블로그 만들기
tags: [Github,blog,jekyll]
excerpt: kiko-now 지킬 테마로 Github 블로그 만들기
comments: true
---

jekyll 테마로 GitHub 블로그(=Github Page)를 간단하게 만들 수 있습니다.

먼저, 맘에 드는 jekyll 테마를 고릅니다.

저는 심플한 [kiko-now 테마](https://github.com/aweekj/kiko-now)를 골랐습니다

![kiko-now](https://user-images.githubusercontent.com/33515697/50897526-b5686380-144f-11e9-8d3a-a7901bd72a3c.png)

jekyll 테마는 디자인적인 부분만 구현되어 있기 때문에 없는 기능(ex. 댓글 달기)들은 각자 **커스터마이징**을 해야합니다. 

처음에는 디자인이 좋아서 kiko-now를 골랐었는데 커스터마이징하기에도 편리해서 추천드립니다. 

다음으로 해야하는 일은 Github 블로그로 사용할 Github repository를 만드는 일입니다.    

--- 

## 내 GitHub에 유저명.github.io 이름으로 repository 만들기
Github에 **1.Fork**를 하거나 **2.Download ZIP**을 클릭해서 본인 Github repository에 추가합니다.

![Fork](https://user-images.githubusercontent.com/33515697/50898812-9b308480-1453-11e9-8104-2e0e3134127e.png)

1 . Fork를 하면 자동으로 Github에 repository가 만들어집니다.

대신 원래 지킬 테마 이름으로 repository가 만들어지기 때문에 Settings에 들어가서 **repository 이름을 변경**해줘야합니다.

![repository 이름 변경](https://user-images.githubusercontent.com/33515697/50898567-ed24da80-1452-11e9-80a1-d3e4188dcf1e.png)

repository 이름은 **유저명.github.io**로 무조건 해야 합니다.(저의 경우 유저명이 Eun0이기 때문에 eun0.github.io로 변경했습니다.)

그리고 유저명.github.io가 블로그 사이트 주소가 됩니다.

만약 Fork로 했는데 안된다 하시는 분은 **2. Download ZIP** 을 클릭해 zip 파일을 다운 받고 압축을 푼 파일들을 **repository에 업로드** 하시면 됩니다.

설정을 마치셨으면 주소창에 **유저명.github.io** (ex. eun0.github.io)를 치시면 블로그가 만들어진 것을 확인하실 수 있습니다.

※ 단, 적용되는 데 시간이 걸리므로 20 초 정도는 기다리셔야 됩니다.















