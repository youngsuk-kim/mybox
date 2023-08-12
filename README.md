## 사용 기술
- Java 17
- Spring Boot 3.1.2
- MySQL 8.0
- QueryDsl
- JPA
- Naver Cloud Platform

## 개발 기간
    2023.08.13 ~ 

## 요구 사항
- [ ] 유저는 로그인을 할 수 있다.
- [ ] 유저는 최대 30GB 까지 파일을 업로드 할 수 있다.
- [ ] 사용자 업로드할 파일의 사이즈가 정해진 용량을 초과 했을 경우 파일 업로드가 실패한다.
- [ ] 파일 업로드가 시작될 경우 즉시 사용가능한 공간이 차감된다.
- [ ] 파일 업로드가 중간에 실패할 경우 사용가능한 공간은 그 전으로 돌아간다.
- [ ] 유저는 다른 유저의 파일에 절대 접근할 수 없다.
- [ ] 폴더 생성시에는 용량이 증가하지 않고, 파일 업로드 시에 용량이 증가한다.
- [ ] 같은 경로에 동일한 이름의 폴더나 파일이 존재할 수 없다.
- [ ] 폴더 depth에는 제한이 없다.
- [ ] 브라우에서 파일 다운로드가 가능해야 한다.
- [ ] 브라우저에서 다운로드 진행상황을 알 수 있게 용량이 표시된다.
- [ ] 폴더 다운로드 시 폴더 이름으로 된 zip 파일이 다운로드 된댜.
- [ ] 파일을 클릭할 경우 다운로드가 된댜.
- [ ] 폴더를 클릭할 경우 하위 리스트가 노출된다.
