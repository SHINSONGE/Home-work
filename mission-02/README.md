
# 로그인 박스 생성
실습을 위한 과제로, mission-2 라는 폴더 안에 login.html, login.css파일을 만든다.

## HTML 마크업의 순서(head 제외)


1. 로그인
- h1 : 헤드의 이름을 주어 현재 파일의 대제목으로 둠
- "log__big-box" 이름으로 바디 안에 박스를 만들어서, 로그인 틀 생성

2. 아이디 레이블 입력서식
- 아래와 form과 fieldset, legenda 코드를 생성해서 아이디와 비밀번호를 구성
- legenda는 hidden 속성으로 숨김
- 각각 label과 input은 div로 감싸고 클래스를 부여함

3. 로그인 버튼 생성

4. 회원가입, 비밀번호 찾기
- div로 묶고, 순서가 중요하지 않기에 ul과 li로 작성


## CSS마크업


1. 로그인 박스(log__big-box)
- 시안대로 모서리를 5px 부여 
  border-radius: 5px;
- 백그라운드를 두가지 색으로 지정 (90deg는 방향을 의미-시계방향임)
  ackground: linear-gradient(90deg,#ED552F,#E8852E); 
- a11yHidden의 값으로 legenda 숨김
- 박스 그림자 생성
  box-shadow: 5px 5px 0px #AAAAAA;

2. 아이디, 비밀번호 레이블 입력서식
- 위쪽 모서리 둥글게 작업
  border-top-left-radius: 5px;
  border-top-right-radius: 5px;
- display를 inline-block로 지정하여 width값 부여
  display: inline-block;

3. 로그인 버튼
- position을 이용하여, 버튼 배치
  position: absolute;
  width: 50px;
  height: 53px;

4. 회원가입, 아이디/비밀번호
- 아래부분만 모서리 지정
  border-bottom-left-radius: 5px;
  border-bottom-right-radius: 5px;
- 왼쪽 기호 제거
  list-style: none;
  padding-left: 0;
- 각 요소들을 display 값을 조정하고, float 값을 조정하여 배치
  display: inline-block;
  float: left;
  float: right;


## 스크린샷
![image](./%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7.png)
