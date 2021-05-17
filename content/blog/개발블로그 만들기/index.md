---
title: 개발블로그 만들기
date: "2021-05-17"
description: 개츠비를 활용하여 개발 블로그를 만들어 본 이야기입니다.
---

개츠비를 활용하여 개발 블로그를 만들고자 한다.
blog를 위한 가장 기본 테마인 [gatsby-starter-blog](https://www.gatsbyjs.com/starters/gatsbyjs/gatsby-starter-blog/)를 사용한다.

## gatsby-starter-blog의 장/단점

#### 장점

- 기본적인 블로그를 위한 기능 제공한다.
- 타입스크립트 제공한다.
- gatsby 3를 지원한다.
- 직접 커스텀을 하기 좋다.
- 기능 추가를 나중에 하면 된다.

#### 단점

- 플러그인을 직접 셋팅해야 한다.
- 댓글 기능이 없다.
- 검색 기능이 없다.
- 디자인이 너무 투박하다. 디자인도 다시 직접 해야한다.

## 고려사항

- 한 article에 대해서 해당 글에 집중할 수 있도록 한다.
  - 다른 메뉴나 다른 글로 넘어가는 링크같은건 보이지 않도록 한다.
  - 주제별로 묶은 경우, 묶은 것들 끼리는 서로 잘 확인 가능하도록 한다.

## 기타 원하는 기능들

쉽지는 않을수도 있지만 한번 넣어보자.

- markdown, code highlight가 잘 되어야 함.
- 그리고...댓글을 쓸수 있어야 한다.
- table of contents 작성
- canvas, p5js, webgl등의 구현
