## React JS의 memo() 활용하기
#### memo를 사용해서 prop의 값이 변경되지 않은 것은 rendering되지 않게 만들어 줍니다.
___
```

const MemorizedBtn = React.memo(Btn);

```

* 기능
  * 버튼을 클릭할 때 변경된 prop 값을 출력하는 프로그램입니다.
  * prop의 값이 변경된 것만 console창에 출력됩니다.

* memo를 사용하는 이유
  * 모든 컴포넌트(Component)를 rendering하면 프로그램 속도가 느려지는 원인이 됩니다.
  * memo를 사용하면 변경된 컴포넌트만 rendering하기 때문에 속도가 느려질 일을 막을 수 있습니다.
