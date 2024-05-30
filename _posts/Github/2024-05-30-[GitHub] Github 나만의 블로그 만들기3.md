---
title: Github 나만의 블로그 만들기(with chirpy)-3
date: YYYY-MM-DD HH:MM:SS +09:00
categories: [Tech, Github]
tags:
  [
Github,Git,블로그,Github page,chirpy
  ]
image : /assets/img/Git_Hub.png
pin: true
published: false
---

## 관련글
* [Github 나만의 블로그 만들기(with chirpy)-1](https://gubeommo.github.io/posts/GitHub-Github-%EB%82%98%EB%A7%8C%EC%9D%98-%EB%B8%94%EB%A1%9C%EA%B7%B8-%EB%A7%8C%EB%93%A4%EA%B8%B01/)
* [Github 나만의 블로그 만들기(with chirpy)-2](https://gubeommo.github.io/posts/GitHub-Github-%EB%82%98%EB%A7%8C%EC%9D%98-%EB%B8%94%EB%A1%9C%EA%B7%B8-%EB%A7%8C%EB%93%A4%EA%B8%B02/)

## 블로그 포스팅 하기

먼저 Clone이 된 폴더 안에 _post가 있는것을 확인 할 수 있는데 앞으로 여기에 Markdown형식의 파일을 올리면 자동적으로 포스팅이 될 것이다.

![image](https://github.com/Gubeommo/TIL/assets/86589565/bb4291cc-796a-4ff5-bd93-c08c9262e757)

아래 보이는 `.placeholder`은 지워주도록 하자.

`_post` 폴더 아래에 파일을 `.md` 형식인 파일을 만들것이다. 파일 제목의 형식은 `YYYY-MM-DD-[글제목].md` 로 작성해야한다.

오늘이 2024년 5월 30일 이므로 제목을 `2024-05-30-나만의 블로그 포스팅.md` 라고 파일 이름을 적어 보겠다.

![image](https://github.com/Gubeommo/TIL/assets/86589565/cf3dd5ef-572f-40e0-8dc4-bb663db1785e)

마크다운 작성법을 모르는 분들을 위해 추후에 정리하여 올리도록 하겠다.
하지만 포스팅 할때에 한가지 규칙이 필요하다.

```yaml
---
title: TITLE
date: YYYY-MM-DD HH:MM:SS +/-TTTT
categories: [TOP_CATEGORIE, SUB_CATEGORIE]
tags: [TAG]     
---
```

참고로 `date` 요소에는 마지막에 `YYYY-MM-DD HH:MM:SS +09:00` 으로해주자 

그외로도 자주 쓰는 요소가
```yaml
pin: true    # 홈 화면에 고정시킬건지
published: true    # 게시 할건지
```

위에있는 형식에 맞춰서 넣은후 그 아래에 내용을 작성하면 된다!.

## 검색엔진 등록

블로그를 포스팅을하고 여러 사람들이 검색을 하여 들어 올 수 있도록 검색엔진에 등록해보자 !

