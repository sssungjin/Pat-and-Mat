# Pat-and-Mat

sungjin

11/22 
로그인(db 연동, 정보 확인해서 맞으면 로그인)
회원가입(db 연동x, 비밀번호, 주민번호 예외 처리, 이메일 인증x)
프로필설정(css x, 이미지 여러 개 처리 x)

11/24
로그인 시 session.getAttribute를 통해 userID 저장
게시판 페이지 boardSite
글 작성 write, writeAction - 작성 시 db에 데이터 저장, 조회수, 추천은 0
로그아웃 logouAction - session.invalidate()로 현재 세션 해제 
seonho
11/23
로그인(css 파일 추가)
회원가입(비밀번호 재확인으로 focus 수정)
인증화면(삭제 검토)
메인화면(css 파일 추가)
매칭화면 추가(profile.jsp파일 include하여서 프로필 화면 연동, css 파일 추가)
프로필 화면 추가(css 파일 추가)
