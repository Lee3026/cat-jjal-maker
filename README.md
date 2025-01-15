# 고양이 짤방 생성기

> 입력한 텍스트와 고양이 이미지를 결합한 짤방을 생성하는 리액트 앱입니다
> [짤방 미리보기](https://milooy.github.io/cat-jjal-maker/)

# 배포 url

```
https://lee3026.github.io/cat-jjal-maker/
```

# JSX

Javascript + XML

> Javascript에 HTML태그를 얹은 리액트에서 사용하는는 문법

# Babel

> JSX => Javascript로 통역

# 상태(useState)

컴포넌트 안에서 자유롭게 변경할 값이 필요할 때

1. const[상태명, 상태변경함수명] = React.useState(초기값)
2. 컴포넌트 안에서 만들 수 있다.

```
const [counter, setCounter] = React.useState(1)

function 카운터증가(){
    setCounter(conter + 1); //(참고) setCounter(prev => prev + 1)로도 가능!
}

return <button onClick={카운터증가}>카운터는 {counter}</button>
```

# Fetch_API

```
https://developer.mozilla.org/ko/docs/Web/API/Fetch_API/Using_Fetch
```

# public API github

```
https://github.com/public-apis/public-apis
```

# 자바스크립트 비동기 처리와 콜백 함수

```
https://joshua1988.github.io/web-development/javascript/javascript-asynchronous-operation/
```

# 자바스크립트 Promise

```
https://joshua1988.github.io/web-development/javascript/promise-for-beginners/
```
