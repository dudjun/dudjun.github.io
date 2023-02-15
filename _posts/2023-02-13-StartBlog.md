---
layout: single
title:  "깃허브 블로그 생성하기"
categories: 블로그
tags:
    - [블로그, 깃허브]

toc: true
toc_sticky: true

published: true

date: 2023-02-13 22:12:30+0900
---

# GitHub Pages란?

깃허브 리포지터리에 간단한 마크다운 형식 파일을 저장하고 설정하면 간단한 웹사이트를 만들어 주는 서비스.

# 1. 테마를 선택하여 포크한다

<https://github.com/topics/jekyll-theme>  
위 링크로 들어가서 테마를 선택한다.  
Fork해서 본인의 깃헙 계정에 복사한다.

# 2. 리포지터리 이름을 바꾼다

Settings에서 리포지터리 이름을   
깃허브 계정 프로필 이름.github.io 로 생성한다.  
ex) dudjun.github.io

# 3. _config.yml 파일 수정하기

url부분에 주석을 삭제하고 내 블로그 주소가 될 이름으로 수정하고 커밋한다.  
이제 그 주소로 들어가보면 블로그가 만들어져있다.  
블로그에 들어갈 다양한 구성을 이 파일에서 수정할 수 있다.
