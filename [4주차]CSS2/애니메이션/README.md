### SS 애니메이션과 JS 애니메이션의 차이에 대해서 설명해주세요

**CSS 애니메이션**

- 미디어쿼리를 통해 반응형으로 애니메이션을 구현하기에 유용하다.
- 외부 라이브러리를 필요로 하지 않는다.
- 애니메이션이 어디서 일어나는지 알아보기 쉽다. CSS는 선언형이라는 특징을 가지고 있어 요소에 직접 애니메이션을 지정해주기 때문이다.
- 메인 스레드가 아닌 별도의 컴포지터 스레드에서 그려지므로 메인 스레드에서 작업하는 JS보다 효율적이다.

**JS 애니메이션**

- 요소의 스타일이 변하는 순간마다 제어할 수 있어 애니메이션을 세밀하게 제어할 수 있다.
- GPU를 통한 하드웨어 가속을 제어할 수 있다. CSS의 경우 특정 속성에 의한 GPU 가속이 성능 하락을 발생시킬 수 있는데 이를 방지할 수 있다.
- 브라우저 호환성 측면에서 CSS보다 뛰어나다.