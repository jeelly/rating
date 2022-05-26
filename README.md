# React 입문 주차 개인 과제
### 내 일주일 평점 남기기

> Q1. 평균 평점 state를 메인 컴포넌트에 두셨나요, 하위 컴포넌트인 평균 평점 컴포넌트에 두셨나요?

메인 컴포넌트

> Q1-1. 선택하신 방식의 장단점은 무엇이라 생각하시나요?

제가 선택한 방식의 장점은 시간이 절약되고 단순합니다.
반대로 컴포넌트를 분리하면 좋은점은 
같은 state를 공유하는 변화된 컴포넌트만 리렌더링을 하여 자원도 아끼고 성능도 올릴 수 있고 재사용성이 좋습니다.


> Q1-2. 평균 평점과 리셋 버튼을 추가할 때 어떤 고민을 하셨나요?

리셋 버튼을 눌러서 평균값을 변경할 때 state의 setter 기능을 이용해야겠다는 생각을 했습니다.

> Q2. 과제 구현 간, 상태관리를 위해 useState를 사용해보고 배운 점을 적어주세요.

리액트는 state가 수정이 일어나면 state가 포함된 DOM을 재 렌더링 해줍니다. SPA를 만들고 싶으면 state에 변경이 필요한 데이터들은 저장해 사용해야 합니다.

> Q3. 랜덤 숫자가 아닌 평점 남기기 페이지에서 입력한 숫자를 반영하기 위해서는 어떻게 해야 할까요?

단방향 데이터 바인딩이기 때문에 부모 컴포넌트가 props 받는 건 안 될 거 같고 리덕스 기능을 이용해야 할 거 같습니다.
