## React JS의 propTypes 활용하기
#### propTypes로 prop의 타입을 설정해서 틀린 값이 들어가면 경고가 발생합니다.
___
```

Btn.propTypes = {
  text: propTypes.string.isRequired,
  fontSize: propTypes.number
}

```


* `text의 타입`은 String이고, `fontSize의 타입`은 Number입니다.
* `isRequired`는 값을 주지 않으면 경고가 발생합니다.
