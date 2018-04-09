---
layout: post
current: post
title: "Started With Jekyll"
date: 2018-03-09T03:53:32+09:00
cover: 
navigation: True
tags: [Getting Started, Jekyll, Octopress]
class: post-template
subclass: 'post'
author: go2zo
---



회사 직원들이 [`hexo`](https://hexo.io/ko/index.html)로 블로그를 만든다는 얘기를 듣고 묵혀뒀던 내 블로그 상태를 보니 [`octopress init`](https://github.com/octopress/octopress#init) 명령만 실행한 상태로 방치되어 있었다.

그 모습을 보고 이런저런 기술 리서치나 개발 이슈들을 내 컴퓨터에 열심히 `.md` 파일로만 모셔두지 말고 보기 좋은 곳에 차곡차곡 정리좀 해야겠다는 생각이 불현듯 들었다.

 ruby보다는 javascript가 그나마 익숙하다는 생각에 **나도 바로 hexo로 갈아탈까?**하는 생각이 들었다가 그래도 오랫동안 정든(?) [`Jekyll`](https://jekyllrb.com/)을 한번 정리하는 샘 치고 `Jekyll + Octopress` 조합으로 한번 리뉴얼을 해보자 마음먹었다.

엇그제부터 어제까지 테마때문에 헤맨거 생각하면 그냥 hexo로 새로 시작했었더라면.. 하는 후회가 남긴 한다.



## Jekyll vs. Hexo vs. Hugo

Jekyll 외에는 아직 사용해보지 않아서 도구의 사용성 등에 대한 비교는 나중에 할 예정이다.

- Jekyll
  - 언어: Ruby
  - 특징: [`octopress`](https://github.com/octopress/octopress)를 쓰면 포스트 작성이 용이하다. octopress는 2015년 v3.0.11 이후로 업데이트가 없지만 최신 jekyll에서도 잘 동작하는 것을 확인했다.
- Hexo
  - 언어: Javascript (Node.js)
  - 특징: jekyll의 octopress가 하는 기능들이 대부분 hexo 자체에 포함되어 있다. 아무래도 javascript 기반이어서 그런지 테마가 잘 되어있다는 평이다.
- Hugo
  - 언어: Go



## 블로그 방향성

블로그를 어느 방향으로, 어느 정도까지 활용을 할 것인가?

Jekyll로 우선 방향을 잡고 [테마](http://jekyllthemes.org/)를 고르다보니 나중에라도 테마를 마구 쉽게 수정(마치 css만 갈아치우듯이)할 수 있을 것 같지 않다는 생각이 들었다.

`_layouts`, `_includes` 등이야 테마에 딸려오는 부분이라 새로 설치하면 되겠지만 post나 page의 머릿말에 테마별로 특화된 머릿말이 첨가되기 때문에 중간에 테마가 변경되려면 이에 대한 수정이 필요하지 않을까 생각(~~아직까진 추측~~)해본다.

그리고 또한 테마별로 랜딩페이지, 블로그, 메뉴, 태그 등 특화된 부분이 조금씩 달라서 내가 필요한 기능에 따라 테마를 먼저 정하고 가기로 했다.

>뭐가 필요할까?
>
>- 글 목록에 제목, 내용일부 외에 작성자, 작성날짜, 태그가 표시되어야 한다.
>- 글 목록에 이미지가 표시될 가능성이 있다.
>- 태그별로 categorize가 가능해야 한다.
>- 글 목록은 페이징이 가능해야 한다.
>- 메뉴는 되도록 상단에 표시되고 반응형이어야 한다.
>- 랜딩페이지는 넣을지 말지 아직 결정은 나지 않았다.

그래서 몇가지 맘에 드는 테마를 추렸다.

- [Jasper2](http://jekyllthemes.org/themes/jasper2/): ghost 기본 테마
- [Jekflix](http://jekyllthemes.org/themes/jekflix/): 깔끔한 footer
- [Prologue](http://jekyllthemes.org/themes/jekyll-theme-prologue/): 메뉴, 하위 메뉴 기능
- [Clean+Simple](http://themes.jekyllrc.org/clean-and-simple/): archives, tags 페이지 참조용
- [Atomos Plus](http://jekyllthemes.org/themes/atmos-plus/): 깔끔한 초기 페이지, [particle](https://vincentgarreau.com/particles.js/) 사용 참조용
- [Tale](http://jekyllthemes.org/themes/tale/): 텍스트 글 목록 스타일

랜딩페이지를 적용한다면 아래 두 테마를 참조할 예정이다.

- [Jekyll-Uno](http://jekyllthemes.org/themes/jekyll-uno/)
- [Cover Card](http://themes.jekyllrc.org/cover-card/)


## 첫 포스팅을 향해

### Jekyll 설치

### Octopress 설치

### Octopress 템플릿

### 테마 설치