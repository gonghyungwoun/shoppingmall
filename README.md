# ShoppingMallProject
> Spring Framework를 사용한 쇼핑몰 웹 프로젝트입니다.   

<br>

## 1. 제작 기간 & 참여 인원
+ 2022년 7월 20일 ~ 2021년 10월 6일
+ 개인 프로젝트

<br>

## 2. 사용기술

#### `Back-end`
+ Java 8
+ Spring Framework 5.0.2
+ Maven 2.5.1
+ MyBatis 3.4.1
+ MySQL
+ Spring Security 5.0.6

#### `Front-end`
+ JQuery 3.1.1
+ Bootstrap

#### `deploy`
+ AWS RDS (MySQL)


<br>

## 3. ERD 설계

<img src="https://user-images.githubusercontent.com/70243735/117144749-45830180-aded-11eb-8570-53637ef14517.png">

<br>

## 4. 핵심 기능

### [ 로그인기능 ]

<img src="https://user-images.githubusercontent.com/70243735/117665271-9f187100-b1dd-11eb-992c-9ca70d3c7115.png" width="900px">

- [X] **로그인기능** 
   <details>
    <summary> 로그인기능 설명 펼치기:pushpin: </summary>
 
   <br>
  
   **[ 기능 설명 ]**   
   : 회원 가입을 할 수 있습니다.   
   : 로그인 이후, 회원 정보 수정을 할 수 있습니다.  
   : Spring Security를 사용하여 로그인을 할 수 있습니다.   
   : Spring Security Handler를 이용하여 로그인 성공, 실패, 접근제한을 처리합니다.

    **[ 상세 구조 ]**

    <img src = "https://user-images.githubusercontent.com/108513349/221596989-e4040604-5a5e-4ca0-b692-4a66f840c42d.PNG" width ="800px">

   </details>
  

### [ 상품창구현 ]   


- [X] **상품창구현**
  <details>
   <summary> 상품 CRUD 설명 펼치기:pushpin: </summary>
   
   <br>
  
   **[ 기능 설명 ]**    
  : 상품은 메인 **이미지가 필수**이며, 서브 이미지도 등록할 수 있습니다.   
  : 관리자만이 게시물을 등록, 수정, 삭제할 수 있으며, 누구나 조회할 수 있습니다.   
  
   **[ 상세 구조 ]**
   
   <img src = "https://user-images.githubusercontent.com/108513349/221596985-cf3691f4-3eca-443f-82ed-9b39bb16303d.PNG" width ="800px">
   
  </details>

- [X] **주문기능**
  <details>
  <summary> 주문기능 설명 펼치기:pushpin: </summary>
  
  <br>
  
  **[ 기능 설명 ]**   
  : 회원은 결제정보를입력후 결제를 하실 수 있습니다.

    **[ 상세 구조 ]**
   <img src = "https://user-images.githubusercontent.com/108513349/221596998-0b663882-718a-4597-b93a-c01367cfe24c.PNG">
     
  </details>
  
    
- [X] **카카오페이 기능**
  
  <details>
  <summary> 카카오페이 기능 설명 펼치기:pushpin: </summary>
  
  <br>
  
  **[ 기능 설명 ]**   
  : **카카오페이**를 이용하여 상품을 결제할 수 있습니다.   
  : 장바구니에 있는 여러 상품들을 **함께 주문**할 수 있습니다.   
  
    **[ 상세 구조 ]**

   <img src = "https://user-images.githubusercontent.com/108513349/221596996-16cb789d-8a60-4d13-92b6-3a1cb21b119f.PNG">
    
  </details>
  
- [X] **카드 결제**
  
  <details>
   <summary> 카드 결제 설명 펼치기:pushpin: </summary>

  <br>
  
  **[ 기능 설명 ]**
   : 결제정보, 응답코드, 거래번호를 콘솔창에 추가했습니다. 
   : 결제하기를 클릭하여 결제 정보를 확인할 수 있습니다.
   
  **[ 상세 구조 ]**
  
   <img src = "https://user-images.githubusercontent.com/108513349/221596994-67c2364b-0b50-4364-b776-b3bc5d480649.PNG">
  
  </details>
  
- [X] **마이페이지**
  
  <details>
   <summary> 마이페이지 설명 펼치기:pushpin: </summary>

  <br>
  
  **[ 기능 설명 ]**
   : 상품이 한번에 표시되도록 추가했습니다.
   : 주문취소 클릭시 주문취소를 확인할 수 있습니다.
   
  **[ 상세 구조 ]**
  
   <img src = "https://user-images.githubusercontent.com/108513349/221596992-fed6bc27-ca52-4c86-9bc2-608d01433b93.PNG">
  
  </details>
  

  
