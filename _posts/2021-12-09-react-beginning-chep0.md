---
layout: post
author: Ghosts
title: React Beginning Chep0
date: 2021-12-09T11:28:03.104Z
thumbnail-img: /assets/img/posts/logo-og.png
category:
- react
- blog
summary: React Beginning Chep0
keywords: blog
thumbnail: /assets/img/posts/logo-og.png
permalink: /blog/categories/react
---
## nodejs 검색후 최신버젼 설치

{% highlight ruby %}
공부하는 과정에서 정리하는 관점에서 작성합니다. 
node 설치 부터 React의 구조 파악에 중점을 두며 
실제 AWS 클라우드 서버에 배포 까지의 과정을 목표로 작성 한다. 
{% endhighlight %}

### nodejs 설치

Create-React-App 라이브러리를 사용하기 위해 우선 nodejs를 설치 하도록 한다. 
nodejs
 홈페이지 접속후 버젼은 테스트 과정이기에 상관없이 다운로드 진행
 nodejs.org
  ![react](/assets/img/posts/reactsetting.png)

### nodejs를 설치가 되면 이제 부터 npm를 사용할수 있다.

`npm 은 nodejs 패키지 관리툴이다.`

### React 기본 프로젝트 생성

nodejs 를 설치 해야지 create-react-app 사용이 가능
`npx create-react-app blog`

vscode 에서 React 설치
  ![react](/assets/img/posts/create-react-app.png)


 설치가 완료된 이후 해당 폴더로 이동후 실행되는지 확인한다.

{% highlight ruby %}
cd project
npm start
{% endhighlight %}

실행이 되는 확인보자 
React의 기본 포트는 3000으로 시작한다.
![react](/assets/img/posts/localbasic.png)

