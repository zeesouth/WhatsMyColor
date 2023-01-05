# What's My Color?
- <b>Personal Color</b> Web Page 💄
- KW 3-2 Web Programming Final Project 
- Duration : 2021.11 ~ 2021.12
<br/>

## 🗓️ Introduction
+ 퍼스널컬러
  + 개인이 타고날 때부터 가지고 있는 신체 색
  + 개인의 피부와 머리카락, 그리고 눈동자색과 가장 잘 어울리는 색
  <br/>
  
+ 왜 퍼스널컬러가 중요할까?
  + 이제는 유행따라 가는 시대가 아닌, 개개인의 <b>개성</b>이 중요한 시대
  + 개인에 따라서 피부색, 머리카락색, 눈동자색 등의 생김새가 모두 다르기 때문에 어울리는 색도 다름
  + 퍼스널 컬러 테스트는 개인에게 가장 잘 어울리는 색을 진단하여 계절에 맞는 색으로 <b>단점은 보완하고 장점은 극대화</b>시켜 <b>긍정적이면서도 자신감 있는 이미지</b>를 연출해줌
  <br/>

## 🛠️ Development Environment
+ Back : Node.js(express), Socket.io
+ Front : HTML5(ejs), CSS3, JavaScript
+ OS : Ubuntu / MacOS
+ DBMS : MySQL
<br/>

## ⛓️ Structure
  <img width="700" align="center" alt="image" src="https://user-images.githubusercontent.com/90493141/205485730-4f12df36-c09e-4e8b-933e-87a5e3ff2280.png">
<br/>

## 🕹️ Feature
<a href="https://github.com/zeesouth/WhatsMyColor#1-home">🏠 HOME</a>&nbsp;&nbsp; • &nbsp;&nbsp;<a href="https://github.com/zeesouth/WhatsMyColor#2-%ED%8D%BC%EC%8A%A4%EB%84%90%EC%BB%AC%EB%9F%AC">☑️ 퍼스널컬러</a>&nbsp;&nbsp; • &nbsp;&nbsp;<a href="https://github.com/zeesouth/WhatsMyColor#3-%EC%BB%AC%EB%9F%AC%ED%8C%94%EB%A0%88%ED%8A%B8">ℹ️ 컬러팔레트</a>&nbsp;&nbsp; • &nbsp;&nbsp;<a href="https://github.com/zeesouth/WhatsMyColor#4-%EC%BB%A4%EB%AE%A4%EB%8B%88%ED%8B%B0">👥 커뮤니티</a>&nbsp;&nbsp; • &nbsp;&nbsp;<a href="https://github.com/zeesouth/WhatsMyColor#5-%EB%A7%88%EC%9D%B4%ED%8E%98%EC%9D%B4%EC%A7%80">⚙️ 마이페이지</a>&nbsp;&nbsp;
<br/><br/>

#### 0. 개요
  + 상단 카테고리 바를 통해 모든 페이지에서 다른 페이지로의 이동이 가능하다.
  + 모든 메뉴는 'HOME' 메뉴를 제외한 회원가입이 된 사용자에 한하여 <b>로그인</b> 상태에서만 이용 가능하다.
  
#### 1. HOME
  <img width="800" alt="image" src="https://user-images.githubusercontent.com/90493141/205528453-c97593a0-727b-4db7-8710-5a99f53926fa.png">
  
  + 로그인 상태에서 'HOME'에서 <b>퍼스널 컬러 검사히기</b> 버튼을 클릭하면 <b>'퍼스널컬러 테스트'</b> 페이지로 이동한다.
  + 로그아웃 상태에서 위와 같은 기능을 동일하게 수행할경우, <b>'로그인'</b> 페이지로 이동한다.
  <br/>
  
#### 2. 퍼스널컬러
  + 퍼스널컬러 테스트 및 퍼스널 컬러 분류에 대한 정보를 제공하는 메뉴
  <br/>
  
  1. 퍼스널컬러 테스트 
  + 테스트 시작 페이지
  
      <img width="800" alt="image" src="https://user-images.githubusercontent.com/90493141/205529169-9e2ec98f-406b-489a-9ec7-1be7abf243fb.png">
    
      + 퍼스널컬러 테스트 시작 전 안내 문구와 함께 테스트 진행 여부에 대해 사용자가 선택할 수 있게 한다.
      + 퍼스널컬러 검사하기 버튼을 클릭하면 본격적인 테스트가 진행된다.
  <br/>
  
  + 테스트 진행 페이지
  
      <img width="800" alt="image" src="https://user-images.githubusercontent.com/90493141/205530231-e8126479-b965-4685-8f1c-c5eb9303127b.png">
      
      + 9가지의 2지선다형 객관식 문항으로 제공된다.
      + 사용자가 보다 정확한 테스트를 진행할 수 있도록 각 문항에 <b>테스트 참고 이미지</b> 및 <b>TIP</b>을 제공한다.
      + <b>이전/이후 버튼</b>을 클릭하여 결과 제출 전까지 문항을 수정할 수 있다.
      + 마지막 문항인 9번 문항으로 이동할 경우 <b>결과보기</b> 버튼이 활성화 되며, 이를 클릭하면 퍼스널컬러 테스트 결과를 알려준다.
  <br/>
  
  + 테스트 결과 페이지
  
      <img width="800" alt="image" src="https://user-images.githubusercontent.com/90493141/205531175-2a079f6e-c79c-4257-a37e-deef892ed1d3.png">
  
      + 사용자의 퍼스널컬러 테스트 결과를 알려준다.
      + <b>더 알아보기</b>버튼은 해당 결과에 대한 자세한 정보를 제공하는 <b>퍼스널 컬러 분류</b> 페이지로 이동시킨다.
      + <b>결과 저장하기</b> 버튼은 사용자의 테스트 결과를 저장하며, <b>'마이페이지'</b>에서도 확인이 가능하다.
  <br/>
  
  2. 퍼스널컬러 분류
  
     <img width="800" alt="image" src="https://user-images.githubusercontent.com/90493141/205533172-3dc72610-8ebd-4f63-99b1-48e503b71c15.png">
     
     + 테스트를 진행하지 않고도 해당 페이지로 이동하여 <b>모든 퍼스널컬러 분류 정보</b>를 볼 수 있다.
     + 테스트 결과 페이지에서 더 알아보기 버튼을 클릭할 경우, 분류 결과에 맞는 페이지로 이동시키며 위와 같이 다른 퍼스널 컬러의 정보도 볼 수 있다.
  <br/>
  
#### 3. 컬러팔레트
  
  1. 옷
  
     <img width="800" alt="image" src="https://user-images.githubusercontent.com/90493141/205535291-6d0dde8e-cd9a-45fa-a96d-8b52710ea31e.png">

     + 각 퍼스널 컬러별로 옷에 대한 컬러팔레트를 제공한다.
     + 사용자 본인의 퍼스널컬러에 맞는 옷 컬러팔레트를 참고하여, 옷을 코디할 때 색상 선택에 도움이 될 수 있도록 한다.
  <br/>
  
  2. 메이크업 제품
  
     <img width="800" alt="image" src="https://user-images.githubusercontent.com/90493141/205535212-70820656-e8bd-4627-8f6b-4b90886332b0.png">
     
     + 각 퍼스널 컬러별로 메이크업에 대한 컬러팔레트와, 색조 화장품 추천 리스트를 제공한다.
     + 사용자 본인의 퍼스널컬러에 맞는 메이크업 컬러팔레트, 추천 색조 화장품을 참고하여 메이크업 제품을 구매하거나 메이크업을 할 때 색상 선택에 도움이 될 수 있도록 한다.
     <br/>
     
#### 4. 커뮤니티
     
  + <b>메이크업, 옷, 기타</b>의 세 가지 카테고리로 커뮤니티 기능을 제공한다.
  + 사용자들이 커뮤니티 기능을 활용하여 각 카테고리 별로 정보 공유를 할 수 있도록 한다.
  <br/>
     
  1. 게시글 리스트 조회 
     
     <img width="800" alt="image" src="https://user-images.githubusercontent.com/90493141/205552044-bc95a907-25eb-49f1-a6b0-f204fbdd707a.png">
     
     + 카테고리 별로 게시글 리스트를 최신 작성순으로 조회한다.
     + <b>제목 또는 작성자</b>를 기반으로 검색 및 조회할 수 있다.
     + 한 페이지당 10개의 리스트를 조회하며, 하단의 페이지 번호를 클릭해 <b>이전/이후의 게시물 리스트를 조회</b>할 수 있다.
     + 작성하기 버튼을 누르면 해당 카테고리의 <b>게시글 작성하기</b> 페이지로 이동한다.
     + 게시글 리스트의 특정 게시물의 제목을 누르면 <b>게시글 상세보기</b> 페이지로 이동한다.
     <br/>
  
  2. 게시글 작성하기
     
     <img width="800" alt="image" src="https://user-images.githubusercontent.com/90493141/205553200-0f68c73e-2f48-4df7-89b2-c6322d481f44.png">
     
     + 제목 및 내용 작성(필수), 파일 첨부(선택)를 하여 작성할 수 있다.
     + 우측 상단의 드롭다운 바를 선택하여 카테고리를 변경하여 게시글을 작성할 수 있다.
     <br/>
  
  3. 게시글 상세보기
  
       <img width="800" alt="image" src="https://user-images.githubusercontent.com/90493141/205553809-338b1768-6116-48f4-9239-40e4dd33d9aa.png">
       
       + 카테고리 별로 모든 작성된 게시물 상세보기가 가능하다.
       + 자신이 작성한 게시글은 수정 및 삭제할 수 있다.
       + 다른사람이 작성한 게시글은 상세보기만 가능하다.
       <br/>
       
  4. 게시글 수정하기
       
       <img width="800" alt="image" src="https://user-images.githubusercontent.com/90493141/205554208-0dec37a1-b052-4378-908e-aa97e150e818.png">
       
       + 제목, 내용, 파일은 수정이 가능하나 카테고리는 수정이 불가능하다.
       + 제목, 내용은 공란 작성(수정)이 불가능하다.
       <br/>

#### 5. 마이페이지
  1. 정보보기/수정
  
       <img width="800" alt="image" src="https://user-images.githubusercontent.com/90493141/205557831-06322c96-96f3-4b48-bdfc-eab605135a8a.png">
       
       + 현재 사용자의 회원정보(이름, ID, 비밀번호, 퍼스널컬러)를 조회할 수 있다.
       + 회원 정보 중 비밀번호만 수정할 수 있다.
       + 퍼스널컬러는 첫 회원 가입 시 공란이다. 퍼스널컬러 테스트를 수행하고 결과를 저장했을 경우, 가장 최근에 저장한 데이터 기준으로 저장 및 조회된다.
       <br/>
       
  2. 탈퇴하기
       
       <img width="800" alt="image" src="https://user-images.githubusercontent.com/90493141/205558412-52a09edd-7fb9-41ff-9e36-82015542986d.png">
       
       + 사용자가 회원 탈퇴를 시도하려는 것이 맞는지에 대한 확인 문구를 제공한다.
       + 현재 사용자의 비밀번호를 올바르게 입력하고 탈퇴하기를 누르면 해당 사용자의 계정이 삭제된다.
       <br/>
       
  3. 로그아웃
  
       + 로그인한 사용자의 세션이 해제되며 메인페이지로 이동된다. 
       <br/>

## 📑 References
+ 퍼스널컬러 테스트 : ~~http://www.colorz.co.kr/~~ (This page is currently closed.)
