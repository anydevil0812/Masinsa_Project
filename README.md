# 마신사 프로젝트
<img width="840" style="display: block; margin: 0 auto;" alt="마신사" src="https://user-images.githubusercontent.com/109947297/210025252-43a9d88e-0a29-4ea5-a286-4fcc1a1f80bb.png">

- **[마신사 링크] - [http://35.216.95.168:3000/](http://35.216.95.168:3000/)**
- **[시연 영상 링크]** - [**https://coding789.tistory.com/168**](https://coding789.tistory.com/168)
- **[API 문서 링크(Swagger)] - [http://35.216.122.45:8080/swagger-ui.html](http://35.216.122.45:8080/swagger-ui.html)**
- **[관련 보고서 파일]**
[**마신사_발표자료_12_23_최종.pdf**](https://github.com/anydevil0812/Masinsa_Project/files/10325154/_._12_23_.pdf)

### [프로젝트 소개]

**마신사는 제각각인 마스크 사이즈로 마스크 구매에 불편함을 겪고 있는 사람들이 간편하게 정보를 습득하여 만족스러운 마스크를 구매할 수 있도록 도와주는 마스크 정보 제공 웹사이트입니다.**

**[진행 기간]**
- 2022.11.28 ~ 2022.12.22

**[진행 배경]**

코로나로 인하여 마스크 착용이 일상화 되어 있고, 다음과 같은 이유들로 사람들이 마스크 구매에 어려움을 겪고 있어 진행하게 되었습니다.

- 마스크 사이즈에 대한 국내 표준 규격이 존재하지 않음
- 리뷰를 읽고 제품에 대해 파악하는데 많은 비용과 시간 소요
- 마스크 판매 서비스에 대한 평점을 제공하는 사이트는 많으나 마스크의 세부적인 특징(사이즈, 착용감, 호흡 등)에 대한 평점을 제공하는 사이트는 적음

**[주요 기능]**

- 마스크의 기본 정보(상품명, 사진, 가격, 옵션, 형태, KF지수, 구매 링크) 제공
- 10000건 이상의 리뷰 데이터를 자연어 처리(NLP)로 분석한 마스크의 통계 데이터(그래프) 제공
- 가장 인기 있는 Top3 마스크 표시 (기준 - 클릭 수 > 평점 > 리뷰 수)
- 검색창 또는 필터링(KF지수, 사이즈, 형태)을 통하여 원하는 조건의 마스크 검색
- 관심 있는 마스크를 따로 체크할 수 있는 찜 기능 (회원만 가능)
- 마스크에 대한 상세 리뷰 확인 및 작성

**[맡은 역할 - 백엔드]**

- 프로젝트 설계 및 아이디어 기획
- 웹 스크래핑을 이용한 데이터 수집
- MySQL을 이용한 DB 설계
- Spring Boot(Maven)를 이용한 MVC 패턴 기반 RESTful API 설계 및 개발
- Spring Data JPA와 MyBatis를 이용한 CRUD 구현
- Postman을 이용한 API 테스트
- Swagger를 이용한 API 문서화
- React와 Spring Boot를 이용한 네이버 로그인 구현
- Docker와 GCP를 이용한 웹 애플리케이션 배포

**[프로젝트 진행 과정]**
- 주제 선정 -> 데이터 수집 -> BMC(Business Model Canvas) 설계 -> 유저 스토리 설계 -> 화면 구성 설계 -> 기능 정의서 작성 및 기술 스택 결정 -> API 명세서 작성 -> DB 설계 -> 개발진행(프론트엔드/백엔드/머신러닝 파트로 분담) -> 프로젝트 배포 및 보고서 작성

**[사용한 기술 스택]**
1. DB
    - MySQL
2. 전처리
    - Python (Selenium)
3. ML/DL
    - KoNLPy
4. 언어
    - Java
    - CSS
    - HTML
    - JavaScript
    - Python
5. 프레임워크
    - React
    - chart.js
    - SpringBoot
    - MyBatis
6. Deploy
    - GCP (SQL Server)
    - Docker
7. Tool
    - Git
    - Notion
    - Slack
    - PostMan
    - Swagger
    - Figma
8. IDE
    - VScode
    - STS
9. 3rd Party API
    - 네이버 로그인 API
    - 네이버 회원 프로필 조회 API

**[소감]**

이번 파이널 프로젝트는 이전 프로젝트들과 다르게 코칭을 해주시는 멘토님이 계셨는데 초반부터 Why -> How -> What이라는 키워드와 “개발자는 단순히 코딩만 하는 사람이 아니다” 라는 개발자라는 직업의 본질과 함께 프로젝트 진행 시 초기 기획 단계의 중요성을 강조하셨고 

이에 따른 가이드라인으로 Why에 대한 부분이 명확히 설명되는 주제 선정, BMC(Business Model Canvas) 및 유저 스토리 설계, 웹페이지 화면 구성 설계, 기능 정의서 및 API 명세서 작성, DB 설계 작업 등 현업에 종사하지 않는 이상 시도조차 생각할 수 없었던 개발 프로세스를 직접적으로 경험할 수 있었습니다.

비록, 이 모든 것들이 저희 팀원 모두가 처음이라 서툴어 기획 및 설계 작업에만 주어진 프로젝트 기간 중 절반 가량이 소요되었지만 내가 이 개발 작업을 진행하는 목적이 무엇이고 내가 구현하려는 이 기능이 왜 필요한지(Why)에 대한 부분을 명확하게 정리해 놓았고 머릿속에 인지함으로써 

업무 파악 등의 코딩 외적인 부분으로 인하여 개발 작업에 차질이 생기는 것을 미리 방지할 수 있었기 때문에 코딩 작업 기한이 12일 밖에 남지 않았음에도 팀원 모두가 적극적으로 의사소통하고 열심히 노력하는 만큼 빠른 속도로 작업을 진행할 수 있어 최종적으로 프로젝트를 무사히 마무리할 수 있었습니다. 

또한, 프로젝트 시작 직전에 배웠던 Spring Boot, MyBatis, Spring Data JPA, MySQL, React를 실전에 적용해보며 복습해보고 Swagger와 Docker, GCP, 네이버 로그인 API과 같이 이전에 배우지 않았던 기술들을 스스로 공부하고 터득하여 결과물을 무사히 도출한 것이 무척이나 뿌듯했던 프로젝트였습니다. 

결론적으로, 공모전 성격이 강하던 이전 프로젝트들과 다르게 개발자라는 직업의 본질을 다시 생각해보고 그동안 배웠던 기술들을 실전에 적용해보는 동시에 추가적으로 필요한 처음 접하는 기술들을 공부하며 개발을 잘 모르는 이들도 한눈에 알아볼 수 있고 이용해 볼 수 있는 결과물을 도출하여 부트캠프 내에서 외부 심사위원의 심사 결과 1등까지 한 것이 무엇보다도 기뻤던 6개월간 진행한 부트캠프에서의 마지막 프로젝트였습니다.

### [프로젝트 진행 중 겪은 문제점]

### **기획 및 설계 문제**

1. 프로젝트 초기에 흥미롭지만 팀원들 모두 **도메인이 부족했던 분야와 관련된 주제**를 선정하였으나 개발 이유인 **Why에 대해 명확한 설명이 부족**했고 이후에 해당 분야에 종사하는 현직자의 조언도 들어보니 도저히 **개발할 이유도 없고 현실적으로 구현 불가능한 주제**라 해당 주제를 **파기**하였습니다.
<br><br> ⇒ 결국, <b>팀원들 모두가 익숙하고 해당 도메인 지식이 어느 정도 있는 주제(마스크)</b>로 선정하여 프로젝트를 진행하였습니다. 이를 통해 확실히 도메인이 부족한 분야는 위험도가 크니 신중하게 생각한 뒤 접근해야 함을 뼈저리게 느낄 수 있었습니다.

2. 마신사라는 주제를 정한 뒤 **기능 정의서를 작성할 때** 저희 팀이 정한 개발 **목적에서 벗어난 기능들(ex- 결제)이 추가**되고 이에 따른 유저 스토리를 먼저 고려하지 않고 **DB부터 설계**하려고 하여 **프로젝트가 원활하게 진행되지 못하고 해당 작업을 반복**하는 실수를 범했었습니다.
<br><br> ⇒ 멘토님께서 다시 가이드라인을 잡아주시고 나서야 다시 차근차근 **BMC 설계**부터 진행하여 프로젝트 기획 및 설계 작업을 무사히 마칠 수 있었습니다.

### **개발 문제**

1. **Spring Boot에서 JPA를 이용하여 Entity 정의** 시에 DB에 **이미 있는 컬럼이 또 다른 컬럼명으로 생성**되는 문제를 겪었습니다. <br><br>
**JPA를 이용하여 컬럼명을 카멜케이스**로 작성할 때 **MySQL에서는 해당 컬럼명을 스네이크 케이스로 자동 변환**하여 **Entity** 구조를 **생성/수정**해주는데
**MySQL에서는** **breathability**라고 입력하고 **Spring Boot에서는 breathAbility**로 컬럼을 정의하여 DB에 **breath_ability라는 새로운 컬럼이 불필요하게 생성**되는 것이 원인이었습니다. 
<br><br> ⇒ **MySQL에서** Truncate를 통해 데이터를 다 삭제한 후 **breathability 컬럼명을 breath_ability로 수정**하니 문제가 해결되었습니다.

<p align="center"><img src="https://user-images.githubusercontent.com/109947297/210240730-1729ea50-446d-481e-9838-d7f1fd9bd9a1.png" height="180"><p>

2. Image 객체의 **외래키 컬럼 데이터**인 maskId를 추출하고자 일단 **MyBatis에서 select문의 resultType**으로 **Mask 객체**를 지정하니 객체 데이터가 반환되지 않고 **null로만 출력**이 되는 문제가 발생하였습니다.
    
<p align="center"><img src="https://user-images.githubusercontent.com/109947297/210240899-e549570e-05f6-49b6-9837-aa51e26bf1ae.jpg" height="180"><p>

이를 해결하고자 **resultType 대신에 resultMap을 사용**하기로 하고 resultMap 정의 시 **PK는 <id>로 나머지 컬럼들은 <result>로 입력**하여 정의하였는데 이 또한 전과 **같은 결과**가 나왔고

<p align="center"><img src="https://user-images.githubusercontent.com/109947297/210240980-b3374076-ed11-41a0-92bd-8eed4011b1c5.jpg" height="200"><p>

**resultMap 정의 시 외래키 관계에 있는 컬럼은 \<result\>가 아닌** <b>\<association\>이나 \<collection\></b>을 사용해야 한다는 점을 발견하여
<br><br> ⇒ \<result\>가 아닌 **\<collection\>을 이용**하여 컬럼에 대한 정보를 입력하였더니 그제서야 **원하는 Mask 객체를 출력**하여 문제를 해결하였습니다.

<p align="center"><img src="https://user-images.githubusercontent.com/109947297/210241115-df23acc1-4f36-4df2-96cb-b0c5e265edef.png" height="180"><p>

여기서 **또 다른 문제점**이 있었는데 Mask 객체에서 **maskId만 추출하여 Image 객체에 저장**하려고 했는데

DTO 설정에서 **Long maskId가 아닌 Mask mask로 정의**해서 **Mask 객체가 프론트로 전달되어 maskId 이외의 불필요한 컬럼들의 데이터도 함께 반환**되어 문제였습니다.

⇒ **Image DTO에서 Mask mask를 Long maskId로 수정**하여 최종적으로 원하는 결과값을 반환받을 수 있었습니다.

<p align="center"><img src="https://user-images.githubusercontent.com/109947297/210241999-44748b14-0039-4adb-b27c-4945c9e555f1.jpg" height="180"><p>

3. **Spring boot에서 Swagger** 세팅 완료 후 서버를 실행하였는데 **org.springframework.context.ApplicationContextException: Failed to start bean 'documentationPluginsBootstrapper'; nested exception is java.lang.NullPointerException**이 발생하면서 서버가 실행되지 않고 종료되는 문제가 발생하였습니다. <br><br> Spring boot **2.6 버전 이후**에 spring.mvc.pathmatch.matching-strategy 값이 **ant_apth_matcher에서 path_pattern_parser로 변경**되면서 몇몇 라이브러리에서 오류가 발생하는 것이 원인이었습니다.

<p align="center"><img src="https://user-images.githubusercontent.com/109947297/210241972-29122608-e2b6-42f4-8e49-cae6daed02f5.png" height="320"><p>

⇒ **application.properties에** **spring.mvc.pathmatch.matching-strategy=ant_path_matcher 입력**하여 default값 변경하여 해결하였습니다.
<p align="center"><img src="https://user-images.githubusercontent.com/109947297/210242414-287b3d5f-a779-448f-a884-50b4d9d5da67.png" height="280"><p>

4. Spring boot로 작업 중에 **DataConversionException**으로 인하여 서버 에러가 발생하는 문제에 직면하였습니다. <br><br> deletion 컬럼 정의 시 데이터 값이 2개(Y/N) 밖에 존재하지 않도록 정했기에 해당 컬럼은 Enum을 이용하여 Entity와 DTO에 정의했는데 깜빡하고 해당 컬럼에 
**@Enumerated(EnumType.STRING)**을 적용하지 않았던 것이 원인이었습니다.

<p align="center"><img src="https://user-images.githubusercontent.com/109947297/210242612-a9a02d6a-baa3-4d01-8d2a-de100ed97969.png" height="280"><p>
 ⇒ <b>@Enumerated(EnumType.STRING)</b>하고 나니 서버가 정상적으로 실행되며 문제가 해결되었습니다.

<p align="center"><img src="https://user-images.githubusercontent.com/109947297/210242759-aff7e722-2b7d-4439-9ae5-faf49006fdaf.png" height="280" width="650"><p>

5. Spring boot로 조회 메소드에 MyBatis를 이용한 pagination 구현을 시도하였지만 **MyBatis mapper.xml 파일에서 TypeException**이 발생하였습니다. <br><br> 분명 MySQL Workbench에서는 잘 실행되는 쿼리문이라 문제점을 찾아보니 **Like문에 대한 조건 입력 시에 '%#{변수}%'으로 입력한 것이 원인**이었는데 <b>#{}</b>으로 변수값을 불러올 경우 자동으로 <b>따옴표('')</b>로 붙어서 **String 형태** 입력되기 때문에 문제가 발생한 것이었습니다.
    
<p align="center"><img src="https://user-images.githubusercontent.com/109947297/210243024-e1a4371e-6c3b-483c-87f6-148e8e10f757.jpg" height="280" width="550"><p>

 ⇒ **#을 $으로 수정함**으로써 문제를 해결하였는데 <b>${}</b>으로 변수값을 불러올 경우 자동으로 **해당 컬럼의 데이터 타입에 맞추어 입력**되기 때문입니다. 추가적으로 이 둘의 차이점을 찾아보니 <b>${}은 #{}보다 편리하지만</b> **쿼리 주입**을 예방할 수 없어 **보안적인 측면에 있어서 더 취약**하다는 점을 알 수 있었습니다.

<p align="center"><img src="https://user-images.githubusercontent.com/109947297/210243184-c4d79e8f-359c-4f85-8b5f-ad0d885468e9.jpg" height="280" width="550"><p>

6. 필터링 기능을 구현한 메소드에서 **IllegalArgumentException**이 발생하는 문제를 발견하였습니다. <br><br> 원인을 찾아보니 **Y와 N만 입력할 수 있도록 JPA에서 Emum으로 정의**한 컬럼에 팀원들 중 한 명이 DB에 테스트 데이터를 입력할 때 **Y나 N이 아닌 test라는 문자열 데이터를 DB에 저장**해놔서 발생한 오류였습니다.  

<p align="center"><img src="https://user-images.githubusercontent.com/109947297/210243670-c930f6ab-fd25-42c9-a459-3a48226a9d66.jpg" height="280" width="550"><p>
⇒  해당 데이터 <b>test를 N으로 수정</b>하니 정상적으로 해결되었습니다.

<p align="center"><img src="https://user-images.githubusercontent.com/109947297/210243733-2dc7af8c-218e-4c4a-8422-e678b691cd6a.jpg" height="280" width="550"><p>

7. 찜 기능 작업 시 동일한 회원 ID와 마스크ID에 대해서 찜 데이터가 DB에 중복으로 INSERT되지 않도록 구현하기 위해서 **INSERT IGNORE INTO**를 사용하였으나 중복값이 입력되는 문제를 겪었습니다. 
    
<p align="center"><img src="https://user-images.githubusercontent.com/109947297/210243813-005017cc-3d57-4f39-906c-ef34f4e8449a.png" height="280"><p>
⇒ 차선책으로 <b>INSERT INTO ~ SELECT ~ FROM DUAL WHERE NOT EXISTS</b> 구문을 이용하여 해당 문제를 해결하였습니다.

<p align="center"><img src="https://user-images.githubusercontent.com/109947297/210243877-10284e55-90c8-4d2b-a5ef-b64a10230d0f.png" height="280"><p>

8. 네이버 API를 처음 사용해보는 상황이라 **React와 Spring Boot**를 이용하여 **네이버 로그인을** **어떻게 구현해야 하는지** 구글링해도 저희 상황이랑 다른 케이스들이라 해결 방법을 찾을 수 없어 막막했었던 상황이 있었습니다. 
<br><br> ⇒ **네이버 개발자 공식 홈페이지**에 올라와 있는 관련 내용들을 **여러 번 정독**하고 **프론트 팀원들과 끊임없이 회의**하여 다음과 같이 정리하니 진행 방향이 명확해졌습니다.

<p align="center"><img src="https://user-images.githubusercontent.com/109947297/210244131-12aecc6f-f1db-42a1-bcf3-7de9b31f7277.jpg" height="280"><p>

9. 네이버 로그인 기능 구현 중 **접근 토큰이 보안상** **JSON 객체로 반환되지 않고 요청 시에 URL 주소값이 바뀌면서 반환**되어 **React**를 이용한 **접근 토큰 추출** 방법에 대한 고민이 생겼었습니다.
<br><br> ⇒  **window.location.href**를 이용하여 해당 url을 추출하여 **split**을 이용해 접근 토큰에 대한 데이터만 추출하여 해결하였습니다.
<p align="center"><img src="https://blog.kakaocdn.net/dn/bhOSQS/btrUNV4NMDg/Hb9kfnV8OEbJQpdITD9Yd0/img.jpg" height="300" width="500"><p>

10. 네이버 로그인 후 네이버 API를 이용한 회원 정보를 조회하는 요청이 계속 거절당하는 문제가 발생하였습니다. <br><br> 알고보니 **BackEnd 서버**에서 네이버 DB로 **회원 프로필 정보 조회 api 호출** 시 **CORS ERROR**가 발생하는 것이었고 해당 문제의 원인을 찾아보니 작업중인 **React 서버(localhost:3000)와 Spring boot 서버의 포트번호(localhost:8080)가 서로 달라서** 네이버에서 보안 상 요청을 거부하도록 설정한 것이 원인이었습니다.
<br><br> ⇒ React에서 http-proxy-middleware를 사용하여 proxy를 통한 우회 후 api 요청하는 방법으로 이를 해결하였습니다.

<p align="center"><img src="https://user-images.githubusercontent.com/109947297/210244513-515389bb-a709-4c34-8a01-17e3d0afbba2.jpg" height="230"><p>
           
