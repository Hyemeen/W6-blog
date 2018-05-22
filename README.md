##### 전체적인 과정
Machenzie의 유트브 강의를 들으며 게시판 페이지를 만들었다. 이전 주에 학습한 CRUD 모델을 사용한 게시판 만들기를 복습하는 느낌이었다. devise gem을 이용하여 로그인 기능을 구현하고자 했다.
<br>
##### 새로 안 내용
로그인 구현하는 devise gem
<br>
##### 오류 내용
- Post의 본문 내용이 아랫부분에 겹쳐 한 번 더 출력되는 오류
- localhost:3000/users/sign_in을 크롬으로 들어가면 "You are already signed in."이라고 뜨는데, 이 화면에서 New Post가 눌리지 않음
- comment 작성은 가능하나 화면에 출력되지 않음. 따라서 댓글 수정 및 삭제가 불가능한 상황.