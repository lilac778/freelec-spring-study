##**`Spring Security` and `Oauth2 Client`**
<BR><BR>OAuth 사용시 `로그인 시 보안`, `회원가입 시 이메일 혹은 전화번호 인증`,
`비밀번호 찾기`, `비밀번호 변경`, `회원정보 변경` 등을 직접 구현하지 않아도 됨

###<BR><BR>`Spring Boot 1.5` vs `Spring Boot 2.0`
<BR>OAuth2 연동 방법이 크게 변동되었지만 `spring-security-oauth2-autoconfigure` 라이브러리 덕에 그대로 사용 가능
<BR>`Spring Security OAuth2`를 사용해야하는 이유
1. 신규 기능 추가
2. Spring Boot 용 라이브러리(starter) 출시
3. 확장 포인트를 고려해서 설계

스프링 부트 2 방식 특징
1. `spring-security-oauth2-autoconfigure` 여부
2. `application.properties` 혹은 `application.yml` 확인