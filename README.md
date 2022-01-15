# 웹 개발 관련 공부 정리하려 만든 공간

## 공부할 것

## 1. Client - Server - DB 관계

- 브라우저 렌더링 과정이란?
- Client, Server, DB 관계?
  - Client 와 Server는 어떻게 데이터를 주고 받는가?
  - Server 에서 DB에 어떻게 접근하는가?
- API를 어떻게 만들어서 사용하는가?
  - HTTP 메서드 종류, 상태, 특징ㅞ 등..
  - Restful API 가 무엇인가>
- 동기와 비동기가 무엇인가?
  - Fetch / Axios 의 작동원리와 방법
  - async / await 의 작동원리와 방법
  - promise 객체?
  - AJAX?
- 미들웨어가 무엇인가?

<<<<<<< HEAD
### 1.1 동기와 비동기

#### 동기

- 요청, 결과가 한자리에서 동시에 일어나야 한다는 약속
- 즉, 요청을 진행하면, 시간이 얼마나 걸리던지 요청한 자리에서 결과가 주어져야 한다.
- 노드 사이의 작업 처리 단위가 동시로 맞춰진다.

#### 비동기

- 요청, 결과가 한자리에서 동시에 일어나지 않을 것이라는 약속
- 즉, 요청을 진행했다고, 결과가 그 자리에서 바로 주어지지 않아도 된다.
- 노드 사이의 작업 처리 단위가 동시로 맞춰지지 않아도 된다.
- 결과가 주어지는데 시간이 걸리더라도, 그 시간 동안 요청한 사람은 다른 작업을 할 수 있다.
- **웹 페이지를 리로드 하지 않고, 데이터를 요청하는 방식으로 Ajax를 통해서 서버에 요청한 뒤 멈춰 있는 것이 아니라, 계속 프로그램은 돌아감**

#### 블록과 논블록 상태

- 블록상태 : 요청을 날린 쪽이 결과가 나올 때까지 다른 일을 수행하지 않고 기다리는 상태
- 논블록상태 : 요청을 날린 쪽이 결과가 나올 때까지 다른 일을 수행할 수 있는 상태

### 1.2 async / await

- 기존의 비동기 처리방식인 callback 함수(실행 순서를 보장할 수 있게 해줌)와 promise의 단점을 보완한다.
- async & await 기본 문법

```js
async function 함수명() {
  await 비동기_처리_메소드명();
}
```

### 1.3 promise 객체

- js 비동기 처리에 사용되는 객체이다.
- 서버에서 받아온 데이터를 화면에 표시할 때 사용한다.
- 즉, 데이터를 받아오기도 전에, 데이터를 다 받아온 것 마냥 화면에 데이터를 표시하려고 하면 오류가 발생할 수 있음

### 1.4 ajax

- Asynchronous Javascript And Xml (비동기식 JS와 XML)
- JS를 이용하여 서버에 데이터를 비동기적인 방식으로 요청하는 것이다.


#### 

=======
>>>>>>> 33687ac795a3d18cce12457077f41f5b086c6eab
## 2. DOM 

- DOM 에 접근하는 방식으로 무엇이 있는가?

### DOM 이란?

- Document Object Model (문서 객체 모델)
- 웹 문서의 모든 요소를 문서화해놓고, JS를 사용할 때 문서화 한 각 요소별로 접근할 수 있도록 도와주는 기능

## 3. HTML/CSS/JS 

- 웹페이지의 레이아웃을 CSS로 어떻게 잡는가?
- History API vs Anchor tag
  - a 태그를 사용하지 말아야 하는 이유
  - url을 변경하는 방법

## 4. SPA

- SPA가 무엇인가?
- SPA를 어떻게 구현하는가?

## 5. Express

- Express 로 서버 구축하는 방법?
- Express 사용 전과 후의 서버 구축 방법 차이?
- Express 에서 사용하는 라이브러리의 종류와 기능

## 6. Webpack과 Babel

- 크로스 브라우징 이란?
- 트랜스 파일링 이란?
- 번들링 이란?
- babel 이란?
- webpack 이란?

## 7. 개발자도구 

- 개발자도구 란?
- 개발자도구 에서 사용할 수 있는 기능은?

## 8. 프로그래밍 패러다임

- 프로그래밍 패러다임에 어떤 프로그래밍 방식들이 있는가?
- 고차함수 란?
- 순수함수 란?
- 함수형 프로그래밍 이란?
- 객체지향 프로그래밍 이란?
- 선언형 프로그래밍 이란?
- 명령형 프로그래밍 이란?
- 불변성 이란?