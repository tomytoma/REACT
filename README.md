# REACT


## ROUTER 적용
* Router를 활용해서 사용자가 입력한 URL을 통해 특정 components를 불러오는 방법 인지
* React 패키지 중 React-router-dom을 이용해서 hashRouter와 Router 컴퍼넌트를 이용하면 이게 생각보다 간편하게 적용됨

## API 활용
* Javascript의 Fetch()함수를 이용해서 데이터를 가져오고 활용할 수 있겠지만 이렇게 하려면 js 경력치가 높아야 될 필요성이 있으니
* Axios 패키지를 활용해서 API에서 데이터를 가져오고(URL값으로 json파일 기반의 데이터 입수 후)
* 입수전과 입수후를 체크해서
* 화면에 데이터 출력

## Props 검사
* API로 입수한 데이터가 원하는 형태와 맞는지 검사 - 숫자인지 문자인지, 배열인지 등등
* Prop-types 패키지를 설치하고
* 검사 후 반영

## 동적 데이터를 다루는 State
* Objects의 데이터가 일부 변경될 경우, 변경된 것만 체크해서 반영
* 추가될 경우 기존 것은 남겨두고 추가된 것만 추가 반영
* 이런 것이 가능하도록 구성한 React.Component가 클래스형 컴퍼넌트 state = {}
