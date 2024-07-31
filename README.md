# 나만의 일기장
1. home: 일기 리스트 랜더링
2. diary: 일기 상세 조회
3. new: 새로운 일기 작성
4. edit: 기존 일기 수정

- type 를 props 로 보내주어 하나의 컴포넌트에서 여러개의 작용들을 할 수 있는 방법슥듭
- useParams으로 URL Parameter으로 보낸 값을, useSearchParams으로 Query String으로 보낸 값을 컴포넌트에서 조회 가능.
- 또한 useSearchParams으로 Quert값 변경 가능

# 학습 내용
- react-route-dom
- 동적 경로 방법 

## react-route-dom
- SPA의 경로 이동 등 아래의 기능 외 여러 유용한 기능을 지원함
- Routes, Route, Link, useNavigate, useParams, useSearchParams 사용법

 
## 동적 경로 방법 (URL , Query)
#### URL Parameter
- 아이템의 id등의 변경되지않는 값을 주소로 명시하기 위해 사용됨

#### Query String
- 검색어 등 자주 바뀌는 값을 주소로 명시하기 위해 사용

## node moudle
- 노드 모듈 설치
```
npm install
```
