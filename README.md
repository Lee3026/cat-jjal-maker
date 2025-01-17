## 고양이 짤방 생성기

- 입력한 텍스트와 고양이 이미지를 결합한 짤방을 생성하는 리액트 앱입니다.

- 수업자료: <https://milooy.github.io/cat-jjal-maker/>

## 배포 url

https://lee3026.github.io/cat-jjal-maker/

## JSX

- Javascript + XML

- Javascript에 HTML태그를 얹은 리액트에서 사용하는 문법

## Babel

- JSX => Javascript로 통역

## 상태(useState)

컴포넌트 안에서 자유롭게 변경할 값이 필요할 때

- const[상태명, 상태변경함수명] = React.useState(초기값)

- 컴포넌트 안에서 만들 수 있다.

```
const [counter, setCounter] = React.useState(1)

function 카운터증가(){
    setCounter(conter + 1); //(참고) setCounter(prev => prev + 1)로도 가능!
}

return <button onClick={카운터증가}>카운터는 {counter}</button>
```

## 리스트(map)

- 배열에서 map을 돌면서 리액트 UI를 반환한다.

```
const favorite = ["이미지1", "이미지2", "이미지3"]

<ul>
{favorite.map(image=> <img src={image}></img>)}
</ul>
```

## 폼(value)

- 사용자의 입력값을 직접 다루기 위해 value로 상태를 관리한다.

```
const[value, setValue] = React.useState('초기값이에요')
function onValueChange(e){
    setValue(e.target.value);
}
<form onSubmit={handleSubmit}>
    <input value={value} onChange={onValueChange} />
    <button type='submit'>제출</button>
</form>
```

## localstorage
- 브라우저에 데이터 저장하기

```
localStorage.setItem('이름', '삼색이')
localStorage.getItem('이름') //삼색이
```
<br>
<br>
<br>

---

#### 스터디 자료

1. Fetch_API <https://developer.mozilla.org/ko/docs/Web/API/Fetch_API/Using_Fetch>

2. public API github <https://github.com/public-apis/public-apis>

3. 자바스크립트 비동기 처리와 콜백 함수 <https://joshua1988.github.io/web-development/javascript/javascript-asynchronous-operation/>

4. 자바스크립트 Promise <https://joshua1988.github.io/web-development/javascript/promise-for-beginners/>

