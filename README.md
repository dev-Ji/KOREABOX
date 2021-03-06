<h2 align="center">KOREABOX</h2>
<p align="center">
  🙍‍♂️Korea IT Academy Project in 2020🙍‍♀️
</p>
<br><br>


### Description
* 영화 예매를 위한 스프링3.0 MVC 기반 사이트입니다.

### Maintainer
* 이지연 :crown:(팀장)
* 유의상 
* 안신혁
* 이슬아

### Contribution
* 프로젝트 및 Github 셋팅 및 관리, 플로우차트 작성, 데이터베이스 설계 및 구축, ER다이어그램 작성
* 예매(예약)시스템 구축(사용자, 관리자), 예약취소 시스템, 마이페이지, 프로그램 전체 예외처리 및 에러페이지

### Period
* 2020/11/20 - 2020/12/09

### Stack
* Language : JAVA, JSP, HTML, CSS, Javascript
* Library : json, cos, JQuery, Lombok
* Framework : Spring3.0 MVC
* Database : ORACLE(MyBatis)

***

### GIF
* 전체화면은 밑에 Youtube URL 주소가 있습니다.
* GIF와 Youtube 영상은 본인이 개발한 파트만 찍었습니다. 나머지는 하단에 캡처!

* 영화예매_1<br><br>
![영화예매_1](https://user-images.githubusercontent.com/73108443/102073791-276d3280-3e47-11eb-82ab-ffaf6fb7ff3f.gif)<br>
 - 일반회원이 예매 할 때 당일포함 3일이내에 영화만 예약 할 수 있으며, 인원을 선택한 뒤 인원에 맞게 좌석을 선택하면 <br>
   나머지 다른 좌석들은 선택이 안됩니다. 또한, 선택한 좌석을 한번 더 클릭시 선택이 풀립니다. <br>
   상영관과 시간, 인원을 다시 선택하면 페이지가 리로딩 되지 않고 좌석보기를 눌렀을때 바로 적용이 됩니다. <br>
   ajax를 이용하여 페이지가 리로딩 되지 않고, 특정 영역만 데이터를 받아서 리로딩 할 수 있도록 하였습니다. <br>

* 영화예매_2<br><br>
![영화예매_2](https://user-images.githubusercontent.com/73108443/102078426-44593400-3e4e-11eb-835e-40d7f9222891.gif)
![영화예매_3](https://user-images.githubusercontent.com/73108443/102078817-e6791c00-3e4e-11eb-8610-350578d48866.gif)
- 동시에 날짜, 상영관, 시간, 좌석이 같은 좌석이 예약되지 않도록, 먼저 예약한 회원이 있으면 예약이 되지 않습니다.<br>
  또한, 예약이 완료된 좌석은 X박스 이미지로 바뀌고, 좌석 선택이 되지 않습니다.<br>
  ajax를 이용하여 코딩하였습니다.

* 예약관리(관리자)<br><br>
![예약관리(관리자)](https://user-images.githubusercontent.com/73108443/102074493-3f918180-3e48-11eb-8bd2-8e4c7d194eda.gif)
- 관리자로 로그인하여 예약 관리로 들어가면 모든 회원이 예약한 목록을 볼 수 있고, 취소 할 수 있습니다.<br>
  ajax 를 이용하여 페이지가 리로딩 되지 않고, 특정 영역만 업로드 될 수 있도록 하였습니다.
* 마이페이지-예약확인 및 취소<br><br>
![마이페이지-예약확인 및 취소](https://user-images.githubusercontent.com/73108443/102075261-597f9400-3e49-11eb-852e-8d73416b26d1.gif)
- 일반 회원이 마이페이지에 예약확인 및 취소로 들어가면 본인이 예약한 목록을 볼 수 있고, <br>
  이미 상영시간이 지난 영화는 목록에서 확인은 가능하지만 취소는 불가합니다.<br>
  ajax 를 이용하여 페이지가 리로딩 되지 않고, 특정 영역만 업로드 될 수 있도록 하였습니다.

***

### Video URL
* https://youtu.be/AunXz5ltHKc

***

### Capture
* 프로젝트 전체 캡처

* 일반사용자 파트
<br>메인페이지_1<br>
![00 메인페이지](https://user-images.githubusercontent.com/58925978/102003396-476afc00-3d4a-11eb-8331-ea73828d9ca6.PNG)<br>
<br>메인페이지_2<br>
![00 메인페이지_2](https://user-images.githubusercontent.com/58925978/102003401-64073400-3d4a-11eb-9bce-cd24df0aa5b3.PNG)<br>
<br>메인페이지_3<br>
![00 메인페이지_3](https://user-images.githubusercontent.com/58925978/102003402-69647e80-3d4a-11eb-9eb2-0dec4fb3ff4c.PNG)<br>
<br>메인페이지_4<br>
![00 메인페이지_4_하단부분](https://user-images.githubusercontent.com/58925978/102003403-708b8c80-3d4a-11eb-87c7-bb2c88dcee2f.PNG)<br>
<br>회원가입_1<br>
![01 회원가입](https://user-images.githubusercontent.com/58925978/102003405-75504080-3d4a-11eb-93cd-718790cbe606.PNG)<br>
<br>회원가입_2<br>
![01 회원가입완료페이지](https://user-images.githubusercontent.com/58925978/102003408-7a14f480-3d4a-11eb-8ebb-05e44fa3c217.PNG)<br>
<br>로그인<br>
![02 로그인](https://user-images.githubusercontent.com/58925978/102003409-7da87b80-3d4a-11eb-8610-b1e032cda0f4.PNG)<br>
<br>마이페이지 - 개인정보 수정 및 탈퇴<br>
![03 개인정보수정탈퇴](https://user-images.githubusercontent.com/58925978/102003412-813c0280-3d4a-11eb-899a-0df57dc18470.PNG)<br>
<br>마이페이지 - 나의 예매 목록<br>
![04 나의예매목록(회원)](https://user-images.githubusercontent.com/58925978/102003413-8436f300-3d4a-11eb-9d47-8111fa89320d.PNG)<br>
<br>현재상영작<br>
![05 현재상영작](https://user-images.githubusercontent.com/58925978/102003414-88631080-3d4a-11eb-8554-afe0d3e672ea.PNG)<br>
<br>상영예정작<br>
![06 상영예정작](https://user-images.githubusercontent.com/58925978/102003415-8d27c480-3d4a-11eb-9445-7fe15f47c5e6.PNG)<br>
<br>영화 상세보기_1<br>
![07 영화 상세보기_1](https://user-images.githubusercontent.com/58925978/102003416-94e76900-3d4a-11eb-923c-23b801177d27.PNG)<br>
<br>영화 상세보기_2<br>
![07 영화 상세보기_2_스틸컷](https://user-images.githubusercontent.com/58925978/102003417-99138680-3d4a-11eb-9a53-bfbc3a58f0c1.PNG)<br>
<br>영화 상세보기_3<br>
![07 영화 상세보기_3_리뷰](https://user-images.githubusercontent.com/58925978/102003418-9e70d100-3d4a-11eb-9452-fbed12fbf131.PNG)<br>
<br>예매하기_1<br>
![08 예매하기_1_날짜선택](https://user-images.githubusercontent.com/58925978/102003425-a4ff4880-3d4a-11eb-9822-d3676f6ba88b.PNG)<br>
<br>예매하기_2<br>
![08 예매하기_2_시간인원선택](https://user-images.githubusercontent.com/58925978/102003426-aaf52980-3d4a-11eb-88f3-90218d36a2fa.PNG)<br>
<br>예매하기_3<br>
![08 예매하기_3_좌석선택](https://user-images.githubusercontent.com/58925978/102003427-b0527400-3d4a-11eb-81d6-d53e3d2e510f.PNG)<br>

<hr>

* 관리자
<br>관리자 영화관리<br>
![09 영화관리](https://user-images.githubusercontent.com/58925978/102003430-bc3e3600-3d4a-11eb-9be2-5095ecdfffad.PNG)<br>
<br>관리자 영화등록<br>
![09 영화등록](https://user-images.githubusercontent.com/58925978/102003431-bd6f6300-3d4a-11eb-8aa4-0b6eaed3d113.PNG)<br><br>
<br>관리자 예매관리<br>
![10 예매관리](https://user-images.githubusercontent.com/58925978/102003433-c4967100-3d4a-11eb-9aa9-c08092bf0660.PNG)<br>
<br>관리자 상영스케줄관리_1<br>
![11 상영스케줄관리_1](https://user-images.githubusercontent.com/58925978/102003435-c5c79e00-3d4a-11eb-801b-4acda02d096d.PNG)<br>
<br>관리자 상영스케줄관리_2<br>
![11 상영스케줄관리_2_모달창](https://user-images.githubusercontent.com/58925978/102003436-c5c79e00-3d4a-11eb-884a-25b43cac337f.PNG)<br>
<br>관리자 상영관관리<br>
![12 상영관관리](https://user-images.githubusercontent.com/58925978/102003437-c6603480-3d4a-11eb-94ab-6df46a15421d.PNG)<br>
<br>관리자 <br>
![13 회원관리](https://user-images.githubusercontent.com/58925978/102003438-c6603480-3d4a-11eb-8787-efff7385d576.PNG)<br>


***

### To-do Project List
* ~Jumtalk~
* ~OP_IT~
* ~KOREABOX~

