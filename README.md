javascript with rails

Mission1. 댓글 달기 + ajax로 구현하기
-------------------------------------

1. input 태그에 값(댓글내용)을 입력한다.
2. submit 버튼을 클릭한다(submit 이벤트 발생)
2. input 태그에 있는 값을 가져온다.
3. 값이 유효한지 확인한다.(빈칸인지 아닌지)
4. 값이 없으면 값을 넣으라는 안내메시지를 뿌린다.
5. ajax로 처리한다.
6. 현재 글은 어딘지, 작성자는 누구인지 파악한다.
7. DB에 댓글을 저장한다.
8. 서버에서 처리가 완료되면 화면에 댓글을 출력한다.


Mission2. 댓글 구현하기(ajax를 통해서)
---------------------------------------

1. form태그 안에 input 태그 만들기
2. submit 이벤트가 발생했을 경우에
3. form 태그 동작하지 않게 하기
4. input 태그 안에 있는 값 가져오기
5. 빈칸인 경우 알림 주기
6. jquery ajax를 이용해서  원하는 url로 데이터 보내기
6. 로그인 하지 않은 경우 알림 주기
7. 서버에서 댓글 등록하기
8. 페이지 refresh 없이 댓글 이어주기