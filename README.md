# HUFS2020SoftwareEngineering

### Why is this project created?
This is the class project of Team 5, Software Engineering Class, Information and Communication Engineering, Hankuk University of Foreign Studies.

### What is the purpose of this project?
When junior and rookie developer starts to work in big scale field work, they should know about UML(Unified Modeling Language) to contribute well in the project. We would use class material to improve our main contribute ability in any programming development.

### Contributor (Team Members)
강병규 / 고현우 / 김현석 / 정윤성 / 👑 홍영빈

### Supervisor Professor
Saehwa Kim (http://eselab.hufs.ac.kr/index.php/Main_Page)

- - -

### 과제 1 : Team Building

* 각 팀은 비대면 소통 진행

   - 카톡 단톡방 개설

      - 가능한 소통은 여기에서 진행
      
      - 별도의 회의록이 필요 없어지는 장점
        
      - 마지막 wrap-up이 필요
      
      - 비대면 미팅 시간 잡기: 카톡 투표 기능을 이용: https://blog.naver.com/PostView.nhn?blogId=worms1603&logNo=221671288671
      
   - Google hangout으로 비대면 미팅

      - 카톡 단톡방에서 google meet 주소 공유
      
      - 채팅 시 가능한 google meet이 아닌 카톡에서 나누는 것이 좋음
      
      - google meet은 특별히 설정을 하지 않는 한 채팅했던 내용이 사라짐
      
   - Github에 프로젝트 팀 페이지 개설
   
* Github 링크 제출 (못 만들었으면, 그냥 문서(ppt)로 제출)

   - 프로젝트 주제

   - 팀 구성원(participants), 각 멤버 역할(role), 각 멤버 역량(skills)
   
   교과서 예시)
   
   |Participant|Roles|Skills|Training needs|
   |:----------|:----|:-----|:-------------|
   |Alice|Team leader|Management: team leader<br>Programming: C<br>Configuration management|UML<br>Communication skills|
   |John|Architecture liasion<br>Implementor|Programming: C++<br>Modeling: UML|Java|
   |Mary|Configuration manager<br>Implementor|Programming: C++,Java<br>Modeling: Entity relationship<br>Databases: relational<br>Configuration management|Object-oriented databases<br>UML modeling|
   |Chris|Implementor|Programming: C++, Java<br>Modeling: Entity relationship<br>Databases: object-oriented|UML modeling|
   |Sam|Facilities management liasion<br>Tester|Programming: C++<br>Testing: whitebox,blackbox|Inspections<br>Java|
      
- - -

### 과제 1 답안
      
   - 비대면 미팅 시간 

   ![kakaotalk1](https://github.com/archer0307/HUFS2020SoftwareEngineering/blob/master/images/kakaotalk1.png)
   
   - Google Hangout으로 비대면 미팅 진행
   
   ![hangout1](https://github.com/archer0307/HUFS2020SoftwareEngineering/blob/master/images/hangout1.png)
   
   - Github Team Project URL
   
   URL) https://github.com/archer0307/HUFS2020SoftwareEngineering
   
   - 프로젝트 주제
   
   Web Publishing & Web Application Server Programming with Spring Framework & Bootstrap. : HUFS ICE homepage renewal.
   
   - 팀 구성원들의 역할과 멤버 역량, 그리고 요구 사항
   
   |Participant|Roles|Skills|Training needs|
   |:----------|:----|:-----|:-------------|
   |강병규|View Publisher|Programming: C, Java|Bootstrap, HTML, CSS, JS|
   |고현우|Service & Mapper Implementor|Programming: Java|UML|
   |김현석|Database Management<br>Tester|Programming: Python, C, SQL<br>Framework: Django|JAVA, UML, mybatis|
   |정윤성|Controller Implementor<br>Master liasion|Programming: C, Java|UML|
   |홍영빈|Team Leader<br>View Publisher<br>Controller Implementor|Programming: C, Java, Python, mybatis, Freemarker<br>Framework: Django, Spring, Bootstrap|UML|
      
- - -

### 과제 2 : Problem Statement

지난 번에 제출한 Project GitHub에 Project 제목과 Project Problem Statement를 추가

Project Problem Statement: 고객(client, customer)과 사용자(end user) 관점에서 기술, 개발자 관점이 아니라. 

 --> 요구사항 (Requirement) 기술

 --> 풀고자 하는 문제 자체를 기술 (Anlaysis 영역):

   * 최소한 개조식 항목 3개~5개

   * 제공하는 기능 (functional) 관점에서 (가능하면 nonfunctional requirement도 기술 가능)

   * 여러분이 만드는 시스템이 제공하는 기능을 사용하는 주체(어떤 사람인지.. 학생, 교강사, 임산부, 노인 등)가 기술되어야 함

   * 이 시스템의 기능을 제공하기 위해서 활용해야 되는 외부 시스템 (기상청 날씨 제공 서버, 식당 CC TV 등)이 있으면 기술해야 함

   * 활용해야 되는 I/O 디바이스(LCD 패널, 브레이크, 엑셀, 특수 버튼, 비콘)가 기술되어야 함
   
 --> 구체적인 기술로 어떻게 하는지는 얘기를 안 해도 됨 (Design 영역) 

1, 2, 4팀은 발표

- - -

### 과제 2 답안

 - 요구사항 (Requirement 영역)
   
   * 게시판에 학생들의 의견 반영을 위한 기능 추가.
   
   * 학기 초 학생들의 서적 구매 편의성을 위하여 한정기간 책 공동구매 탭이 필요함.
   
   * 영업시간 내에 학교 생활에서의 애로 및 건의사항 해결을 위하여 학과 조교님과 학부생의 실시간 채팅 상담 기능 추가.

 - 풀고자 하는 문제 (Anlaysis 영역)
   
   * "학과 홈페이지"의 "교과과정 탭" 에서, 학부생들에게 다음과 같은 상세한 학과 과목의 정보를 제공.

      1. 학과 교육이수에 필요한 전공 서적.
      2. 원활한 수업 이해를 위한 전공관련 배경지식. (이수요구사항)
      3. 학기 초에 담당 교수님 배정 이후 교과목 교수님의 정보 자동 제공.
      4. 한국외국어대학교 종합정보시스템과의 연계로 선택 교과목의 강의계획서를 볼 수 있는 링크 제공.
      
      현재 교육과정 탭)
      
      ![curriculum](https://github.com/archer0307/HUFS2020SoftwareEngineering/blob/master/images/curriculum.png)
      
   * 학과에서 운영하는 스터디룸 예약 시스템 제공.

   * 한국외국어대학교 정보통신공학과에 관심이 있는 대학 진학 예정자, 정보통신공학과 학부생, 학부 편입생 등이 사용하는 주체가 될 예정.

   * 전공 서적 가격 비교를 위해 각 서적 사이트의 전공 책 가격 비교 시스템 구축.
   
   * 보안을 위한 도구
      
      1. 공유기를 활용한 포트포워딩.
      2. 공유기를 통한 중국발 외부 IP 및 포트 원천 차단.
      3. 소스코드 내부의 HashMap을 extends한 CamelMap을 활용하여 메소드에 접근 할 수 없게 제한.
   
   * 활용되는 Input/Output 디바이스.
      
      1. 보안에 상대적으로 Linux 보다 안전한 Windows 서버 컴퓨터 사용.
      2. 서버 컴퓨터 내부의 대용량 하드 디스크 필요.

 - 대략적인 디자인 (Design 영역)
   
   * 현대적인 홈페이지에 어울리는 세련된 디자인 감각.
   
   * 홈페이지의 약간 부족한 직관성을 보완하여 디자인적 요소를 Bootstrap Framework를 활용하여 개선.
   
   * 교과과정에 자유롭게 과목을 추가하고 제거할 수 있는 UI 구성, 전면적인 구성 개편 필요.
   
- - -
