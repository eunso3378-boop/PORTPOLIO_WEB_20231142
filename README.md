# C# 소스 코드 깃허브
 새로운 시작 ! C#의 세계로 떠나보아요 ~ 

## Getting Started

This project is a starting point for a C# application.

A few resources to get you started if this is your first Flutter project : 

- [프로젝트 메인 주소](https://github.com/eunso3378-boop/C_SHARP_PROJECT)


## DAY 1 - OT (사캠 1주차)
- 강의 일정 확인

 

## DAY 2 - 환경설정 및 깃 허브 연동, C# 기초 살펴보기 (사캠 2주차)
- 실행 및 깃 허브 연동 확인 완료 !
- 스프링 부트 개발 환경, 테스트 완료
• [index.html : 실행/수정 완료][깃허브소스코드URL](src/main/resources/templates/index.html)
- 2주차 연습문제 
  : URL 맵핑과 컨트롤러 추가하기 완료 (두번째 헬로 페이지, 5개의 속성을 각자 추가, hello2.html 작성, 5개 속성 변수를 출력) [hello2.html](src/main/resources/templates/hello2.html)


  
## DAY 3 - 포트폴리오 작성 (사캠 3주차)
- 개인 포트폴리오 템플릿, 프로필 수정하기, 상세 페이지
- 3주차 포트폴리오 작성하기 완료 : 개인 포트폴리오 템플릿 수정
• [index.html : 실행/수정 완료][깃허브소스코드URL](src/main/resources/templates/index.html)
- 3주차 연습문제
  : 상세 페이지 수정하기 완료
  about_detailed.html & main.js 수정해 되돌아가기 버튼 클릭하면 창 닫기 팝업창 뜸, 확인 클릭 시 상세 페이지 닫아짐
  [about_detailed.html](src/main/resources/templates/about_detailed.html)
  <img width="2507" height="1352" alt="image" src="https://github.com/user-attachments/assets/e4942bc0-5a61-408f-a81b-1cbad96a50ff" />
  <img width="1861" height="1000" alt="image" src="https://github.com/user-attachments/assets/ad92c2ee-f9dd-43ae-b2fb-91e0bb460bd9" />



   
 
## DAY 4 - 데이터베이스 연동 (사캠 4주차)
- 웹 트렌드 분석 / 데이터베이스 / MYSQL
- 4주차 : 프로필 수정, Thymeleaf 기본 작성, MYSQL 연동 및 정상 접속 확인 / localhost:8080/testdb 접속 확인
- 4주차 연습문제
  : 사용자 2명 추가 및 출력 완료 (MYSQL 확장 활용, 컨트롤러 수정, testdb.html 뷰 수정)
  [testdb.html](src/main/resources/templates/testdb.html)

  

## DAY 5 - 데이터베이스 연동 (사캠 5주차)
- 5주차 블로그 게시판 시작하기 완료
- [index.html : 실행/수정 완료](src/main/resources/templates/index.html)
- 5주차 연습문제
  : 페이지 리다이렉트 (게시판 글쓰기 후 전체 목록 화면으로 자동 전환, 기존 @RestController 방식을 @Controller 방식으로 수정) 완료
  [BlogController.java](src/main/java/com/example/demo/controller/BlogController.java)
  [BlogRestController.java](src/main/java/com/example/demo/controller/BlogRestController.java)  <-- 전체 주석 처리함
  <img width="2389" height="1032" alt="image" src="https://github.com/user-attachments/assets/c04c5c1d-c1d2-46b4-98c6-088e859502cc" />



## DAY 6 - 6주차 (추석)


## DAY 7 - 데이터베이스 연동 (사캠 7주차)
- 6주차 : ORM 매핑과 영속성
- 실습 : 프로필 수정하기, 블로그 게시판(수정), 블로그 게시판(삭제)
  실제로 작업한 프로젝트 이미지를 넣음.
  [article_error.html](src/main/resources/templates/error_page/article_error.html)
- 6주차 연습문제
  : 새로운 예외용 에러 페이지 추가 
  [article_type_error.html](src/main/resources/templates/error_page/article_type_error.html)
  기존 BlogController.java 수정
  [BlogController.java](src/main/java/com/example/demo/controller/BlogController.java)



## DAY 8 - 출석 및 중간고사 공지 (유튜브)


## DAY 9 - 9주차 (중간고사)


## DAY 10 - 웹 데이터 : JPA Repository
- 7주차 : 게시판 수정 및 추가 기능 완료
   [index.html : 실행/수정 완료](src/main/resources/templates/index.html)
   [board_view.html : 추가 완료](src/main/resources/templates/board_view.html)
- 7주차 연습문제
  : 추가 수정 구현 완료
  [BlogController.java](src/main/java/com/example/demo/controller/BlogController.java)
  [AddArticleRequest.java](src/main/java/com/example/demo/model/service/AddArticleRequest.java)
  [board_edit.html](src/main/resources/templates/board_edit.html)  // 글 수정 버튼 동작을 위한 맵핑 구현
  [board_list.html](src/main/resources/templates/board_list.html)  // 수정 후 board_list.html 로 연결


## DAY 11 - 웹 서버 성능 최적화
- 9주차 : 게시판 수정하기 –삽입 / 게시판 기능 추가 –검색창과 페이징 완료
   [board_list.html : 검색창, 페이징](src/main/resources/templates/board_list.html)
   [BlogController.java : 검색 구현](src/main/java/com/example/demo/controller/BlogController.java)
   [BlogService.java : 저장 기능](src/main/java/com/example/demo/model/service/BlogService.java)
- 9주차 연습문제
  : 게시판 페이지 – 글 번호 (페이지 제한) , 삭제 기능 완료
  [board_list.html : 글 번호 & 삭제 기능](src/main/resources/templates/board_list.html)
  [BlogController.java : 글 번호 & 삭제](src/main/java/com/example/demo/controller/BlogController.java)  //컨트롤러로 부터 시작 페이지를 전달, 글 번호를 출력하게 수정, 삭제 맵핑 및 확인 (글 번호는 순서대로 출력)


  
## DAY 12 - 스프링 시큐리티 & 로그인 로그아웃
- 10주차:
- [로그인 화면](src/main/resources/templates/login.html)
  <img width="2123" height="906" alt="image" src="https://github.com/user-attachments/assets/935e9b5d-ba7d-4b08-838b-05f91d017795" />
- [SecurityConfig.java 생성](src/main/java/com/example/demo/config/SecurityConfig.java) // 로그인 로그아웃 보안
- [회원가입 화면](src/main/resources/templates/join_new.html)
- <img width="2234" height="1204" alt="image" src="https://github.com/user-attachments/assets/318fd8ea-788b-4552-9475-a9b233f87d2a" />
- [회원가입 완료 화면](src/main/resources/templates/join_end.html)
- 10주차 연습문제
  : 입력값 필터링  pom.xml에 의존성 모듈 추가, AddMemberRequest.java 수정 완료
  [AddMemberRequest.java : 검증 처리](src/main/java/com/example/demo/model/service/AddMemberRequest.java)



  
## DAY 13 - 로그인 로그아웃
- 11주차 로그인과 로그아웃–2 완료
- [SecurityConfig.java : 보안 기능을 추가](src/main/java/com/example/demo/config/SecurityConfig.java)
- [MemberController.java : 맵핑 로그아웃](src/main/java/com/example/demo/controller/MemberController.java)
- [board_list.html : 상단 로그인 옵션](src/main/resources/templates/board_list.html)
- [BlogController.java : email 세션](src/main/java/com/example/demo/controller/BlogController.java)


## DAY 14 - 로그인 로그아웃
- 12주차 구현 완료
- [upload_end.html 생성](src/main/resources/templates/upload_end.html)
- [FileController.java 생성](src/main/java/com/example/demo/controller/FileController.java)
- [index.html : 프로필 최종 수정](src/main/resources/templates/index.html)
- <img width="2559" height="1599" alt="image" src="https://github.com/user-attachments/assets/03c46d6c-5a78-4f9f-be25-9f155d14d6cb" />
- <img width="2559" height="1599" alt="image" src="https://github.com/user-attachments/assets/80ce707a-88ce-46a2-85b6-c98c9e08d9d8" />
- <img width="2524" height="1599" alt="image" src="https://github.com/user-attachments/assets/1406ceda-321f-4f1d-80ce-ca72c7d34f50" />
- <img width="1883" height="1599" alt="image" src="https://github.com/user-attachments/assets/0b8df534-20aa-42e7-8fe5-8ef7741bd53d" />
- <img width="2527" height="1599" alt="image" src="https://github.com/user-attachments/assets/62466b95-c197-4c3f-acc0-ba5b284fa800" />
- <img width="2528" height="1599" alt="image" src="https://github.com/user-attachments/assets/f2d0e556-0a6b-40f7-9de0-2b1201fe6063" />






