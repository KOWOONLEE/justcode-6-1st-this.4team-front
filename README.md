<img src="https://velog.velcdn.com/images/hh1008/post/8bf080da-6a3c-4cbd-881e-f41fb3fbb0e3/image.png" width="200px"/>


### 이거사조팀의 **`Hola!`** 사이트 제작 프로젝트입니다.
<img width="500" alt="1st_projectpicture" src="https://user-images.githubusercontent.com/108816777/213902493-ab6ff08f-aa4d-4e37-a348-6ca109cfc664.png">
<br>
👉[Hola 오리지널 페이지](https://holaworld.io/)

---

<br>

## **프로젝트 소개**

```
개발 관련 스터디, 프로젝트 동료 구하는 사이트로 기술 스택 별로 게시글을 보여주며, 사용자가 글
을 작성 및 댓글을 남겨 원하는 팀원을 구할 수 있습니다.
```

<br>

### **프로젝트 구현 영상**

[![HALLO 팀원 모집 커뮤니티 사이트 유튜브 동영상](http://img.youtube.com/vi/ETs8lwviMBw/0.jpg)](https://www.youtube.com/embed/ETs8lwviMBw) 

<br>

## **팀 노션**

📝[이거사조](https://www.notion.so/wecode/4-4193b03c5f434d29a5c055fff938b777)


### **개발 인원 및 기간**

- 개발기간 : 2022/8/29 ~ 2022/9/8
- 개발 인원 : 6명
- 프론트 엔드 : 이혜림, 안승섭, 박유빈, 이고운
- 백 엔드 : 김현정, 안수철
- [프론트엔드 Github 링크](https://github.com/wecode-bootcamp-korea/justcode-6-1st-this.4team-front)
- [백엔드 Github 링크](https://github.com/wecode-bootcamp-korea/justcode-6-1st-this.4team-back)

--------------------------------
## 📌 이고운 담당 상세 내용 📌
### 1. 프로젝트 내 역할
  - 로그인
  - 이용약관
  - 회원가입

<br>

### 2. 구현 상세 내용
**1) 로그인**
- 아이디 @필수 입력, 비밀번호 6자리 필수 입력 필수 조건
- 위의 조건이 만족하면 버튼 활성화 및 버튼 색상 변경됨 
- post method이용하고 token 값 받아와서 올바르게 회원가입하여 계정이 있는 아이디와 패스워드로만 로그인 가능
- 미 충족시에 버튼을 클릭하게 된다면 하단에 로그인 정보를 확인하라는 오류 메세지 alert창 뜸.
- 올바른 정보로 로그인했을 때 로그인이 성공하였습니다라는 alert창이 뜨고 main페이지로 이동됨.
![로그인](https://user-images.githubusercontent.com/108816777/213903085-81cec9b1-64c0-4693-955d-34fe5faa5f16.gif)

<br>

**2) 이용약관**
- 전체동의에 체크한다면 하위 동의 3개에 자동 체크, 전체동의 체크 해제시에 하위 동의 3개에 자동 체크 해제됨.
- 개별 하위 동의가 전부 체크되면 전체동의에 자동 체크, 전체동의 상태에서 하나라도 미체크시 전체동의 체크 해제됨.
- 위의 조건들이 충족 시에 버튼 색상 변경 및 버튼 활성화되고 미충족 시 버튼 클릭한다면 전체 동의해달라고 하단에 오류 메세지 뜸.
- 약관 자세히 보기 modal창을 만들어서 위의 기능 중복 처리
- 전체 동의 후 다음단계 버튼 클릭 시 회원가입 페이지로 이동
![이용약관](https://user-images.githubusercontent.com/108816777/213902769-321c9893-ffd1-43b3-98c8-fe51b5cb8f55.gif)

<br>

**3) 회원가입**
- 닉네임 1자 이상, 이메일 @포함, 패스워드와 패스워드 확인이 동일한 조건일 때 회원가입 가능
- post method이용하고 status값 이용하여 중복확인 알람 뜸.
- 올바른 조건이 충족시에 버튼 활성화 및 색상 변경
- 각각의 조건이 미 충족시에 입력칸 하단에 오류 메세지 출력 (이메일 양식 확인해라, 비밀번호 재확인해라)
![회원가입](https://user-images.githubusercontent.com/108816777/213902937-818761fe-bd23-4ed9-b2a4-11eab899fbd6.gif width='500px')

<br>



--------------------------------
## 👉 전체 프로젝트 내용
### 역할 분담

- 이혜림
  - header nav
  - footer
  - 새글 작성 UI 및 api 연동
  - 사용자 수정 UI 및 api 연동
- 안승섭
  - 메인 화면 UI, 내 글 목록 화면 UI
  - 무한 스크롤, API 연동
  - 각종 버그 수정
- 박유빈
  - 게시글 상세페이지 UI
  - 게시글 삭제 및 뒤로가기
  - 댓글 리스트 UI
  - 댓글 작성, 수정 , 삭제
- 이고운
  - 로그인
  - 이용약관
  - 회원가입
- 김현정
  - 회원가입 및 로그인
  - 사용자 정보 가져오기 및 정보 수정
  - 게시글 목록 가져오기
  - 게시글 선택 내용 읽기
  - 기술 스택 목록 읽어오기
- 안수철
  - 게시글 작성, 수정, 삭제
  - 댓글 불러오기, 작성, 수정, 삭제

<br>

### **프로젝트 선정이유**

- e-commerce 사이트의 경우 조회에 관련된 기능들이 메인으로 조회 기능에 치우쳐서 프로젝트를 진행하기 보다는 밸런스있게 CRUD를 경험하고자 선정하였습니다.
- 이미지 저작권 문제 해소

<br>

## **적용 기술 및 구현 기능**

### **적용 기술**

> **Front-End** : Javascript, React.js, sass, slick, react-modal, create portal

> **Back-End** : Node.js, express, Bcrypt, JWT, RESTful API

<br>

### **구현 기능**

📌[API 명세서 ](https://documenter.getpostman.com/view/22723177/VUxNR7mw#dd4ed3cb-7fdc-4575-8732-19c22d916e9b)

**회원가입**

- 아이디와 비밀번호를 입력 받아 가입할 수 있는 간단한 회원 가입 API.
- 아이디의 중복 여부 체크, 그리고 비밀번호를 해시 함수로 암호화하는 기능이 포함되어 있습니다.

**로그인**

- 입력 받은 아이디와 비밀번호를 받아와 로그인할 수 있는 API
- 사용자는 로그인을 성공적으로 마쳤을 경우 토큰을 발급 받을 수 있습니다.

**사용자 정보**

- 로그인한 사용자에게 발급 된 토큰으로 아이디를 확인하여 정보를 가지고와 수정하는 API
- 발급 된 토큰으로 알맞은 사용자가 요청하였는지 확인 후 수정이 진행됩니다.

**기술 스택 리스트**

- 기술 스택의 목록을 읽어오는 API
- 각 기술 스택의 카테고리에 알맞는 것을 보여주는 필터링 기능과 인기 목록의 경우 자주 작성된 기술 스택 중 상위 10개를 보여주도록 하였습니다.

**게시글 목록 읽어오기**

- 작성된 게시글 목록을 읽어오는 API
- 게시글에 선택된 기술 스택으로 검색할 수 있는 필터링 기능과, 한 화면에 보여지는 게시글 수를 조정할 수 있는 페이징 기능이 포함되어 있습니다.

**게시글 내용 읽어오기**

- 목록에서 선택된 게시글의 내용을 보여주는 API

**게시글 작성**

- 게시글을 작성하는 API
- 발급 된 토큰으로 어떤 사용자가 작성하였는지 구분하여 데이터베이스 테이블에 데이터가 삽입됩니다.

**게시글 수정&삭제**

- 게시글을 수정&삭제하는 API
- 발급 된 토큰으로 구분하여 게시글 작성자와 로그인 한 유저가 같아야 수정 혹은 삭제가 가능하게 구현하였습니다.

**댓글 읽어오기**

- 게시글에 작성된 댓글을 읽어오는 API

**댓글 작성**

- 댓글을 작성하는 API
- 발급 된 토큰으로 어떤 사용자가 작성하였는지 구분하여 데이터베이스 테이블에 데이터가 삽입됩니다.

**댓글 수정&삭제**

- 댓글을 수정&삭제하는 API
- 발급 된 토큰으로 구분하여 댓글 작성자와 로그인 한 유저가 같아야 수정 혹은 삭제가 가능하게 구현하였습니다.

