# (주) 에스앤피랩 기업과제
### Installation

```
npm install
```

### Run

```
npm run server
npm run dev
```


## 개발 인원 및 기간

- 개발기간 : 2022/07/21 ~ 2022/07/27
- 개발 인원 : 프론트엔드 5명
### 랜딩페이지
<img src="https://user-images.githubusercontent.com/90256059/181163370-a302ff7c-fe60-4f06-b92d-50b8873abc64.PNG" width="70%">

### 크라우드 워커 지원페이지
<p>
<img src="https://user-images.githubusercontent.com/90256059/181163788-b3c5f483-7c56-4671-86e5-ed15943f94bc.PNG" width="20%">
<img src="https://user-images.githubusercontent.com/90256059/181163879-0d6c5210-1d7b-4e4b-afd9-9cf92dd2a689.PNG" width="20%">
<img src="https://user-images.githubusercontent.com/90256059/181164039-59e4cddc-342a-4146-bb51-7c4c37f16019.PNG" width="20%">
<img src="https://user-images.githubusercontent.com/90256059/181164113-d155aa56-762d-491c-8d2f-e82a1e466bfa.PNG" width="20%">
</p>

### Admin 페이지
<img src="https://user-images.githubusercontent.com/90256059/181164173-5a07be52-c030-4c5f-85db-9495f1c178e5.PNG" width="70%">

## 팀원 및 구현 기능
### 조혜빈
- 메인페이지 내에서 지원자 리스트 컴포넌트(ApplicantsList) 구현
- 받은 데이터에서 회차별 필터링
- 데이터에 회차 개수 만큼 탭 개수 구현
- 회차별 필터링한 데이터 내에서 페이지네이션 구현
- 체크박스 클릭시 지원자 당첨여부 업데이트

### 이성진
- 앱화면(크라우드 워커 지원 페이지)
  - 정보 입력
    - form 입력, 검증 구현
    - 메뉴 표시를 위한 모달 구현
    - 상호작용에 의한 CSS 적용
  - 거주지역 선택
  - 개인정보 처리방침
  - 제3자 정보제공 동의 안내
  - 입력완료
  - 지원 완료
### 정윤서
- Api 모듈 
  - useCache
    - saveInCache 함수로 전달받은 데이터를 ref에 저장하여 리렌더링시에도 변경되지 않게 저장
    - returnCache 함수로 저장된 데이터를 리턴
  - useAddress
    - getAddressApi 로 대한민국의 모든 시를 받아와 cache에 저장
    - searchAddress 로 모든 시가 들어가 있는 cache를 불러와 검색된 시의 코드를 비교하여 , 모든 구를 받아옴
  - useRegister
    - getApplicants 로 전달받은 매개변수가 없으면 모든 지원자를 받아오고 , 매개변수가 있다면 검색어로 지원자를 filter하여 받아옴
    - postApplicants 함수로 처음 지원자 등록 데이터를 database.json에 저장
    - updateApplicants 함수로 합격여부 변경시 accepted변수 변경
### 김영호
- CSV 다운로드 구현
- phoneFormat 구현

### 한운기
- 메인페이지 레이아웃
- 검색기능 구현
- 검색 항목별 데이터 요청

### Installation

```
npm install
```

### Run

```
npm run server
npm run dev
```

