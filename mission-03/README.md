# 관련 사이트 목록 Transition 활용하여 동작하기
실습을 위한 과제로, mission-3 라는 폴더 안에 transition.html, transition.css파일을 만든다.

## HTML 마크업의 순서(head 제외)


1. section
- h2와 ul을 하나의 섹션으로 묶어서 만든다.

2. UL
- 모든 리스트를 링크를 걸 수 있게 a태그를 넣고 순서가 필요 없는 ul로 묶는다.


## CSS마크업


1. section & h2
- section에 class로 "big-box"로 생성한 뒤 가장 바깥 박스의 레이어를 꾸민다.
- h2 중에 뒤에 "사이트"부분은 따로 span으로 묶은 뒤 오렌지 컬러를 입혀준다.

2. ul
- ul요소에 font와 배경색을 수정한다.

3. a
- a 요소에 플렉스를 주고, align-items을 center로 줘서 세로정렬을 하고, height를 a요소만큼 준다.
- overflow를 hidden으로 주어 칸이 작은 현재 바깥으로 나와있는 글자들을 숨김처리 해준다.

4. ul:hover
- height를 시안의 길이만큼 145px을 주고, transition의 값을 부여한다.


## 스크린샷
https://user-images.githubusercontent.com/134567654/244958230-5fce239a-b577-4ae7-b0c4-c872e8bda9c1.mov
