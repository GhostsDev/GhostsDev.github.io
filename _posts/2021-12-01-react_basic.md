---
layout: post
author: Ghosts
title: React Beginning Chep1
date: 2021-12-09T11:28:03.104Z
category:
- react
- study
summary: React Beginning Chep1
keywords: blog
thumbnail: "/assets/img/posts/logo-og.png"
usemathjax: false
---

## React 구조   ✨
  ![react](/assets/img/posts/folder.png)
  - 기본적인 React 구조를 확인 할 수 있다. 
```jsx
/* index.js */
import React from 'react';
import ReactDOM from 'react-dom';
import './index.css';
import App from './App';
import reportWebVitals from './reportWebVitals';

ReactDOM.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>,
  document.getElementById('root')
);
reportWebVitals();
```
- App.js 기본 메인페이지 들어갈 HTML 코딩을 짜는곳 
```jsx
/* App.js */
import import logo from './logo.svg';
import './App.css';

function App() {
  return (
    <div className="App">
      <header className="App-header">
        <img src={logo} className="App-logo" alt="logo" />
        <p>
          Edit <code>src/App.js</code> and save to reload.
        </p>
        <a
          className="App-link"
          href="https://reactjs.org"
          target="_blank"
          rel="noopener noreferrer"
        >
          Learn React
        </a>
      </header>
    </div>
  );
}
export default App;
```

### ReactDOM이란 
- React는 모듈화 ReactDOM이 실행이 되면 App에 담겨져 있는 내용을 public/index.html 경로에 있는 id='root'에 렌더링 하도록 되어있는 구조이다. 

~~~ruby
/* public/index.html line 27~31 */
    <title>React App</title>
  </head>
  <body>
    <noscript>You need to enable JavaScript to run this app.</noscript>
    <div id="root"></div>
~~~

- 실제 메인페이지를 렌더링 해서 보여주도록 한다. 
- document.getElementById('root')
- App.js -> index.html 
- node_modules 
- 수많은 라이브러리 저장된 폴더 
- public : public 웹사이트 static 파일들 보관함  
- src : 소스 코드 보관함
- package.json : 설치한 라이브러리 목록