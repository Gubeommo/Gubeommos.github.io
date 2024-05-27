---
title: Github 나만의 블로그 만들기(with Jekyll)-1
date: YYYY-MM-DD HH:MM:SS +09:00
categories: [Tech, Github]
tags:
  [
Github,Git,블로그,Github page,chirpy
  ]
image : /assets/img/Git_Hub.png
pin: true
published: true
---

>사실 이미 블로그는 만들어져 있지만 잘 정리된 블로그도 많았다. 하지만 그대로 따라 하다가 여러가지 에러 상황에 마주쳤고 정신없이 하루가 지나가 있었다. 이런 수모를 덜어내기 위해 기록,공유 할겸 다시 한번 정리해본다.

## Jekyll 테마 

우선 블로그에 적용할 `Jekyll`테마를 선택해야한다.

* [https://jamstackthemes.dev/ssg/jekyll/](https://jamstackthemes.dev/ssg/jekyll/)
* [https://jekyllthemes.io/](https://jekyllthemes.io/)
* [https://jekyll-themes.com/](https://jekyll-themes.com/)


마음에 드는 지킬 테마를 다운로드 하자.(이번 포스팅은 아래에 있는 chirpy Theme로 진행)

[https://github.com/cotes2020/jekyll-theme-chirpy](https://github.com/cotes2020/jekyll-theme-chirpy)


---

## Github Repository 만들기

본인의 깃허브에 들어가 레포토리지를 만들면 된다. 방식은 자유롭게 하되 몇가지 규칙이 있다. GitHub 페이지에서 직접 `Repository`를 만들자면


![image](https://github.com/Gubeommo/TIL/assets/86589565/97c3d60e-00fe-469c-a9a2-9c85d80e24f3)

`New` 버튼을 누든뒤

![image](https://github.com/Gubeommo/TIL/assets/86589565/4dc26ce9-4e7d-41fc-ac53-c21514faffa1)

* `Reposity name` : 이름을 설정해주면 된다. 계정명.Github.io로 하자
* `Description` : 깃에 대한 설명인데 간략하게 적어도 괜찮고 안해도 그만이다.
* `Add a README file` : README 파일을 자동으로 추가할것인지 선택하는 칸이다. 간략하게 확인용도로 추가해보자


설정을 확인했으면 `Create repository`를 눌러 생성하자 

> 위에 보이는 The repository kobommo7208.github.io alreadt exits on this account. 는 이미 만들었기에 발생함으로 크게 신경 쓰지 않아도 된다!.

![image](https://github.com/Gubeommo/TIL/assets/86589565/ae4c7b36-0dc4-47ff-8add-56c1fefda2c5)

README 에 나오는 내용은 크게 중요하지 않으며 대략 이런 구성으로 생성 되면 성공한것이다!

> 예전에 깃허브 부계정을 만든적이 있는게 그게 4년전인가보다...

---
## Git Clone

앞으로 깃허브 블러그를 포스팅이나 수정을 할때 Git을 활용을 해야하는데 평소에 본인이 쓰던 툴을 사용하면된다.
평소에 `VSCODE`를 쓰기에 `VSCODE`로 설명을 합니다~ 
>만약 VSCOCE가 첨이거나 git연동이 안되어있는 분들을 위해 추후에 정리후 블로그에 올릴 예정

![image](https://github.com/Gubeommo/TIL/assets/86589565/d5471a3a-90fc-4d6d-88f8-40c645b96696)

먼저 **Code**를 클릭해 나온 Repository 주소를 복사합니다.
복사후 
![image](https://github.com/Gubeommo/TIL/assets/86589565/1013ff9d-cfba-44ab-9f3c-8384e0bb9427)

**Clone Repository** 클릭후 나오는 칸에 주소를 붙여넣고 **Clone**을 할 폴더를 선택후 진행하면


![image](https://github.com/Gubeommo/TIL/assets/86589565/24a66880-5220-4f6e-8c60-20cb696a80b3)

성공적으로 **Clone**이 된다 !

> 앞으로 여기서 작업을 이어가게될 것이며 블로그 포스팅하여 Git commit 혹은 push도 여기서 작업하게 될것이다!
{: .prompt-tip }
---
## Ruby 다운로드 

`Github 블로그` 만드는데 `Ruby`를 다운로드 해야하는건.. `Jekyll` 테마가 `Ruby`로 만들져 있기에 실제 글을 써보고 여러가지 테스트를 해볼수 있다.

[Ruby 다운로드 사이트](https://rubyinstaller.org/downloads/) 들어가면 

![image](https://github.com/Gubeommo/TIL/assets/86589565/2925a255-fd48-469b-824e-435ae5076a35)

이런 페이지가 나오게 되는데 자신의 윈도우 버전에 맞게 다운로드를 진행하면된다. 

본 포스팅은 **Ruby+Devkit3.2.4-1(x64)** 로 다운로드하여 진행합니다~.

그 후에 별다른 설정 없이 계속 Next로 눌러 진행하면된다.

![image](https://github.com/Gubeommo/TIL/assets/86589565/27795893-2e52-4e08-8be4-e014286a1aa2)

이런 화면이 나왔다면 정상적으로 설치가 된것이다.

---

이렇게 `Jekyll` 테마와 Git 레포토리지 생성 , 루비 설치가 끝나면 기초적인 베이스는 준비가 된것이다. 다음에는 직접적으로 테마를 적용해보자