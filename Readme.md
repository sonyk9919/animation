# CSS 애니메이션과 JS 애니메이션

FE 개발에서 애니메이션은 CSS 애니메이션과 JS애니메이션으로 나뉜다.

- CSS 애니메이션의 특징
  - 외부라이브러리를 필요로 하지 않는다.
  - 직관적인 표현이 가능하다.
  - 미디어 쿼리를 사용해서 반응형으로 애니메이션 구현이 가능하다.
  - 별도의 쓰레드에서 그려지기 때문에 JS보다 효율적이다.
- JS 애니메이션의 특징
  - 세밀한 애니메이션 구현이 가능하다. ex) 상호작용시 데이터가 추가, 삭제, 변경되는 애니메이션
  - 브라우저 호환성이 좋다.
  - GPU를 통한 하드웨어 가속을 제어할 수 있다.

# CSS 애니메이션

- CSS의 transition과 가상 클래스 (:hover :focus :active)의 조합으로 간단한 애니메이션을 생성할 수 있다.
- CSS의 transition과 transform을 이용하여 애니메이션을 생성할 수 있다.
- CSS의 가상클래스 (:after :before)를 이용해 다채로운 애니메이션을 생성할 수 있다.
