# 📒 가계부 작성 및 일기 기록 웹서비스 Salog

<div align="center">
<img width="1082" alt="main" src="https://github.com/kimtjrgus/salog/assets/120611048/52114883-7a5f-43b0-8a3a-a26072be37a3">

  ### 프로젝트 기간 : 2023.11.17 ~ ing

  ### 배포 링크 : <a href="http://www.salog.kro.kr" target="_blank">Salog</a>

</div>

<br>

### 주의사항
  - 주요 변경 내역은 dev/be 브랜치에 있습니다.
  - main 브랜치는 배포용 브랜치로 사용 중이기 때문에 Sync fork 하지 않습니다.
  - 자세한 코드는 dev 브랜치에서 확인할 수 있습니다.
  - 새로운 프로젝트는 지양하고 현재 프로젝트를 지속해서 유지보수 중 입니다.

<br>
<br>
<br>

## ✔ 목차
- [📄 기획서](#-기획서)
- [💡 브랜치 전략](#-브랜치-전략)
- [🔧 기술 스택](#-기술-스택)
- [🛠 아키텍처 다이어그램](#-아키텍처-다이어그램)
- [👥 팀원 구성](#-팀원-구성)
- [👨‍💻 개인 역할](#-개인-역할)
- [💻 모니터링](#-모니터링)
- [🖥️ 페이지 별 기능](#️-페이지-별-기능)
- [🎆 개선 목표](#-개선-목표)
- [📢 피드백](#-피드백)
- [🎉 프로젝트 후기](#-프로젝트-후기)

<br>
<br>
<br>

## 📄 기획서

<a href="https://docs.google.com/spreadsheets/d/1_bI9UAymfg1Typ5DVZzbXZe_OQ08q-AZO9Ve1Ph1SL8/edit#gid=0" target="_blank">사용자 요구사항 정의서</a>
<br />
<br />
<a href="https://docs.google.com/spreadsheets/d/1_bI9UAymfg1Typ5DVZzbXZe_OQ08q-AZO9Ve1Ph1SL8/edit#gid=256906179" target="_blank">기능 명세서</a>
<br />
<br />
<a href="https://docs.google.com/spreadsheets/d/1_bI9UAymfg1Typ5DVZzbXZe_OQ08q-AZO9Ve1Ph1SL8/edit#gid=89922257" target="_blank">API 명세서</a>
<br />
<br />
<a href="https://docs.google.com/spreadsheets/d/1_bI9UAymfg1Typ5DVZzbXZe_OQ08q-AZO9Ve1Ph1SL8/edit#gid=1572238774" target="_blank">테이블 명세서</a>
<br />
<br />
<a href="https://docs.google.com/spreadsheets/d/1_bI9UAymfg1Typ5DVZzbXZe_OQ08q-AZO9Ve1Ph1SL8/edit#gid=1829469387" target="_blank">코드 컨벤션</a>

<br>
<br>
<br>
  
## 💡 브랜치 전략

- Git-flow 전략을 기반으로 main, develop 브랜치와 feature 보조 브랜치를 운용했습니다.
- main, develop, Feat 브랜치로 나누어 개발을 하였습니다.
  - main 브랜치는 배포 단계에서만 사용하는 브랜치입니다.
  - develop 브랜치는 개발 단계에서 git-flow의 master 역할을 하는 브랜치입니다.
  - Feat 브랜치는 기능 단위로 독립적인 개발 환경을 위하여 사용하고 merge 후 각 브랜치를 삭제해주었습니다.

<br>
<br>
<br>

## 🔧 기술 스택

### Common
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)

### Front-end
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)
![Styled Components](https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
<img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
<img src="https://img.shields.io/badge/amazon s3-569A31?style=for-the-badge&logo=amazon s3&logoColor=white">


   
### Back-end
<img src="https://img.shields.io/badge/java-1E8CBE?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/intellijidea-000000?style=for-the-badge&logo=intellijidea&logoColor=white">
<img src="https://img.shields.io/badge/spring boot-6DB33F?style=for-the-badge&logo=spring boot&logoColor=white">
<img src="https://img.shields.io/badge/spring security-6DB33F?style=for-the-badge&logo=spring security&logoColor=white">
<img src="https://img.shields.io/badge/JPA-007396?style=for-the-badge&logo=java&logoColor=white">
<img src="https://img.shields.io/badge/mySQL-4479A1?style=for-the-badge&logo=mySQL&logoColor=white">
<img src="https://img.shields.io/badge/JWT-d63aff?style=for-the-badge&logo=JWT&logoColor=white">
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

<br>
<br>
<br>

## 🛠 아키텍처 다이어그램

![샐로그 아키텍처 다이어그램](https://github.com/kimtjrgus/Salog/assets/120611048/300386c0-c927-48b5-b327-a55a60825886)

<br>
<br>
<br>
    
## 👥 팀원 구성

<div align="center">

  |<img src="https://github.com/codestates-seb/seb43_main_004/assets/120611048/fd4b071f-c773-4a17-b27f-ec9656290fa5" width="130px" />|<img src="https://github.com/codestates-seb/seb43_main_004/assets/120611048/1c7f47bc-6dba-4d67-b189-5ac3148256fd" width="130px" />|<img src="https://github.com/codestates-seb/seb43_main_004/assets/120611048/c194e140-fb6b-4bec-8b60-5b8398258e86" width="130px" />
|:---:|:---:|:---:|
|[이용석](https://github.com/021Skyfall)|[김석현](https://github.com/kimtjrgus)|[선유준](https://github.com/YujunSun0)
|BE (팀장)|BE|FE|

</div>

<br>
<br>
<br>

## 👨‍💻 개인 역할

### A. 인증 기능
#### a. 회원가입 시스템 설계 및 구현
- **⚙️작업 내용**    
  + 이메일/소셜 가입 분리 시스템 아키텍처 설계
  + 이메일 중복 검증 기능 개발   
  + Spring Security 기반 권한 계층 구조 구성   

- **🔍방법**   
  - ▶ **자체 회원가입**   
    + `Auditable` 클래스 상속으로 가입 일자 자동 기록   
    + `CustomAuthorityUtils`를 통한 기본 권한(USER) 부여   
    + `BCryptPasswordEncoder`로 패스워드 암호화   
    + 메일 검증 : 구글 SMTP 서버 연동 인증 코드 발송   
  
  - ▶ **소셜 회원가입**   
    + `Google OAuth 2.0` 표준 인증 구현   
    + 구글 API 응답 데이터 파싱 → 이메일 정보 추출 및 저장   

- **💡결과 및 성찰**
  - ▶ **실제 서비스 적용 결과**   
    + 소셜 가입 도입 후 신규 사용자 70% 선택   
    + 이메일 검증 시스템으로 비정상 가입 시도 90% 감소   

  - ▶ **기술적 성찰**   
    + 외부 서비스(구글 OAuth/SMTP) 장애 시 대응 전략 필요성 인지   
    + 사용자 피드백 기반 기능 개선의 효과 체감   
    + 인증 시스템의 안정성 확보 중요성 재확인

#### b. 회원 RUD

#### c. 로그인
- **⚙️작업 내용**  
  + 자체 및 소셜 로그인 시스템 구현  
  + JWT 기반 인증 및 인가 처리  

- **🔍방법**  
  - ▶ **자체 로그인**  
    + 가입한 이메일과 패스워드를 사용하여 로그인  
    + 데이터베이스와 통신하여 해당 회원 존재 여부 확인  
    + 회원 정보를 바탕으로 JWT 생성 및 반환  
    + 서비스 요청 시 요청 헤더에 액세스 토큰 입력 → 회원 구분 및 인가 처리  
    + JWT 페이로드에는 회원 식별자, 이메일 주소 (username), 이메일 주소 (subject), 생성 시간, 만료 시간이 포함  

  - ▶ **소셜 로그인**  
    + 데이터베이스에 해당 소셜 로그인 회원의 이메일이 존재하는 경우, 회원 조회 후 JWT 발급 및 반환  
    + 회원가입 시 이메일 중복을 방지하기 위해 소셜 가입 회원의 경우 이메일만을 DB에 저장하고, 소셜 로그인을 통해 인증 처리가 완료된 것으로 간주하여 JWT를 발급  

- **💡결과 및 성찰**  
  - ▶ **실제 서비스 적용 결과**  
    + JWT 기반 인증 도입으로 회원 보안 개선  
    + 소셜 로그인 사용자 증가에 따른 사용자 경험 향상  

  - ▶ **기술적 성찰**  
    + JWT 관리 및 보안 강화 필요성 인지  
    + 다양한 로그인 방식에 대한 사용자 선호도 파악의 중요성  

#### d. 로그아웃
- **⚙️작업 내용**  
  + JWT 블랙리스트 처리 시스템 구현  

- **🔍방법**  
  - 요청 헤더에 담긴 JWT 액세스 토큰을 블랙리스트라는 List에 삽입  
  - 모든 서비스 요청 시 요청 헤더에 담긴 토큰을 블랙리스트에서 조회  
  - 블랙리스트에 존재할 경우 로그아웃 에러 반환, 존재하지 않을 경우 정상적인 서비스 접근 허용  

- **💡결과 및 성찰**  
  - ▶ **실제 서비스 적용 결과**  
    + 로그아웃 처리 안정성 확보  
    + 사용자 세션 관리 용이성 향상  

  - ▶ **기술적 성찰**  
    + 블랙리스트 관리의 효율성 및 성능 최적화 필요성 인지
    + 조회 성능이 가장 빠른 자료구조에 대한 검토 필요  
      - 예를 들어, HashSet이나 HashMap을 활용하면 O(1)의 평균 조회 성능을 제공하여 블랙리스트 관리에 유리할 수 있음.  
      - 이를 통해 로그아웃 처리 시 성능 저하를 방지하고, 사용자 경험을 개선할 수 있음.  

#### e. 토큰 재발급
- **⚙️작업 내용**  
  + JWT 재발급 API 구현  
  + 리프레쉬 토큰 기반 인증 처리  

- **🔍방법**  
  - "/refresh" API로 요청 바디에 리프레쉬 토큰 포함  
  - 요청 바디의 리프레쉬 토큰을 활용하여 JWT 재발급  
  - 리프레쉬 토큰 기반으로 역할, 식별자, 이메일을 담은 클레임 재생성  
  - 새로운 액세스 토큰 및 리프레쉬 토큰 생성 후 클라이언트에게 응답  
  - 기존 사용 토큰은 보안을 위해 블랙리스트에 추가  

- **💡결과 및 성찰**  
  - ▶ **실제 서비스 적용 결과**  
    + 토큰 재발급 처리로 사용자 편의성 증대  
    + 보안 강화 조치로 사용자 신뢰 확보  

  - ▶ **기술적 성찰**  
    + 리프레쉬 토큰 사용에 대한 주류 방식 파악의 중요성  
      - 현재 리프레쉬 토큰 사용 방식에 대한 고민 필요  
      - 보안 취약점이나 성능 저하를 방지하기 위해 삭제 여부 검토  
    + 보안과 사용자 경험 간의 균형 필요성 인지  

#### f. 이메일 인증
- **⚙️작업 내용**  
  + 회원 가입 시 이메일 인증 시스템 구현  
  + 비밀번호 찾기 시 이메일 인증 처리  

- **🔍방법**  
  - ▶ **회원 가입**  
    + 이메일은 회원의 핵심 정보이므로, 가상의 이메일 주소 사용 방지를 위해 연락 가능한 이메일인지 확인  
    + 중복 이메일 체크 후, 중복되지 않을 경우 해당 주소로 인증 번호 전송  
    + 인증 코드는 알파벳과 숫자를 포함한 4자의 랜덤 문자열로 생성  
    + 이메일 전송을 위해 `EmailSender` 클래스를 구현하고, 구글 메일 서버와 587 포트로 통신하여 이메일 전송  

  - ▶ **비밀번호 찾기**  
    + 비밀번호 찾기는 회원의 중요한 정보를 다루므로, 보안을 위해 이메일 인증 절차를 거침  
    + 회원 가입 시와 유사하게 인증 이메일을 전송하여 사용자의 신원을 확인  
	  + 비밀번호를 Bcrypt 알고리즘으로 해시하여 저장하기 때문에 데이터베이스에서 직접 확인할 수 없으며, 새로운 비밀번호 생성을 유도함

- **💡결과 및 성찰**  
  - ▶ **실제 서비스 적용 결과**  
    + 이메일 인증 도입으로 회원 가입 및 비밀번호 찾기 과정의 보안 강화  
    + 사용자 신뢰도 향상 및 불법 가입 시도 감소  

  - ▶ **기술적 성찰**  
    + 이메일 인증 시스템의 안정성 확보 필요성 인지  
    + 외부 서비스(구글 메일 서버) 장애 시 대처 방안 필요  

<br>

### 2. 가계부 기능
#### a. 수입
- **⚙️작업 내용**  
  + 수입의 생성, 조회, 업데이트 및 삭제(CUD) 기능 구현  

- **🔍방법**  
  - ▶ **수입 CUD**
  
  - ▶ **월별 수입 조회**  
    + 페이지네이션을 위해 페이지와 사이즈를 파라미터로 전달받음  
    + `date`를 전달받아, `date`의 일(day)이 00인 경우 해당 월 전체 수입을 조회하고, 일반적인 일자인 경우 해당 일자의 수입을 상세 조회  
    + `date`는 문자열로 받아오며, 배열을 사용하여 연도(year), 월(month), 일(day)로 나누어 각 조건에 맞게 조회  

  - ▶ **월별 수입 합계 조회**  
    + 분석 페이지를 위한 수입 합계 조회 기능  
    + 태그별 및 월별로 각 수입의 합계를 계산하여 반환  

  - ▶ **날짜 범위 조회**  
    + 사용자 피드백을 반영하여 날짜 범위를 지정하여 수입을 조회할 수 있는 기능 추가  
    + 시작 날짜와 종료 날짜를 받아 해당 날짜에 포함된 모든 수입을 조회  
    + 모든 날짜는 파라미터로 받아 문자열에서 Java의 `LocalDate`로 변환 후 조회  

  - ▶ **수입 태그 관리**  
    + 태그는 별도의 테이블로 구성되며, 수입과 일대다 관계를 형성  
    + 기존에 존재하는 중복된 태그가 있을 경우 해당 태그와 연결하고, 중복되지 않는 경우 새 태그를 생성하여 수입과 연결  
    + 수입을 삭제할 경우, 연결된 태그가 존재하면 태그와의 연결만 끊고 수입만 삭제하며, 태그가 더 이상 연결된 수입이 없다면 태그도 삭제  

- **💡결과 및 성찰**  
  - ▶ **실제 서비스 적용 결과**  
    + 수입 관리 기능을 통해 사용자 편의성 증대  
    + 수입과 태그 간의 관계를 명확히 하여 데이터 관리 용이성 향상  

  - ▶ **기술적 성찰**  
    + 수입 조회 기능의 최적화 필요성 인지  
    + 사용자 피드백을 반영한 기능 추가를 통해 서비스 개선 방향 확인 

#### b. 고정 수입
- **⚙️작업 내용**  
  + 고정 수입의 생성, 조회, 업데이트 및 삭제(CRUD) 기능 구현  

- **🔍방법**  
  + 조회 시 년도와 월을 파라미터로 전달받아 특정 달의 고정 수입을 반환  
  + 고정 수입 데이터는 사용자가 자주 발생하는 수입을 미리 설정하여 관리할 수 있도록 구성  

- **💡결과 및 성찰**  
  - ▶ **실제 서비스 적용 결과**  
    + 고정 수입 기능 도입으로 사용자 편의성 증대  
    + 반복적인 수입 관리의 효율성 향상  

  - ▶ **기술적 성찰**  
    + 고정 수입 데이터의 유효성 검사 및 오류 처리 필요성 인지  
    + 사용자 피드백을 통해 기능 개선 방향 모색  

#### c. 예산
- **⚙️작업 내용**  
  + 월별 예산의 생성, 조회, 업데이트 및 삭제(CRUD) 기능 구현  

- **🔍방법**  
  + 조회 시 년도와 월을 파라미터로 전달받아 특정 달의 예산을 반환  
  + 해당 달의 전체 일수를 계산하고 현재 시간으로부터 남은 일자를 계산하여 반환  

- **💡결과 및 성찰**  
  - ▶ **실제 서비스 적용 결과**  
    + 예산 관리 기능을 통해 사용자 재정 계획 수립 용이  
    + 예산 초과 및 부족을 사전에 파악할 수 있는 기반 마련  

  - ▶ **기술적 성찰**  
    + 예산 계산 로직의 최적화 필요성 인지  
    + 다양한 사용자 요구를 반영한 예산 기능 추가 가능성 탐색  

<br>

### 3. 기타 기능 및 역할
#### a. 유효성 검사
- 클라이언트에서 요청 시 기존에 상의된 데이터 구조를 바탕으로 각 DTO에 정규표현식으로 Validation을 처리했습니다.
- 다른 대규모 웹사이트를 참고하여 상식적으로 허용 가능한 선으로 정의했습니다.

#### b. 배포
- **도메인**
  - 무료 도메인 사이트인 [내도메인.한국](https://xn--220b31d95hq8o.xn--3e0b707e/)을 사용했습니다.
  - www.salog.kro.kr 을 CNAME으로, value는 클라우드 프론트 주소를 할당했습니다.
  - server.salog.kro.kr 을 CNAME으로, value는 서버가 배포된 aws ec2의 퍼블릭 DNS 주소를 할당했습니다.
- **플로우**
  - 깃헙 액션을 통해 자동 CI/CD를 구축했습니다.
  - 프로젝트 메인 레포지터리의 메인 브랜치에 변경 사항을 머지하면 깃헙 액션이 실행됩니다.
  - 깃헙 액션이 실행되면 gradle.yml 에 정의해둔 스크립트대로 프로젝트를 jar 빌드합니다.
  - 이후 도커 허브에 로그인한 뒤 정의해둔 dockerfile 을 기반으로 도커 이미지를 빌드합니다.
  - 빌드된 이미지를 로그인한 도커 계정의 허브로 push합니다.
  - aws ec2에서 해당 이미지를 도커 허브에서 pull 받고 컨테이너에서 실행시켜 서버가 배포됩니다.
  - 필요한 환경 변수는 깃헙 액션 시크릿에 정의해두어 jar 빌드시에 한 번, 도커 컨테이너에서 이미지를 실행시킬 때 한 번씩 주입됩니다.
  - 도커에 대한 내용을 학습하기 위해 [블로깅](https://021skyfall.github.io/posts/salog_project_deploy1/)했습니다.
- **데이터 베이스**
  - 데이터 베이스는 AWS RDS를 사용합니다.
  - 프리티어에 맞는 사용량으로 구축하였으며 프로젝트 설정 파일(application-deploy.yml)에 url과 username, password와 driver class를 정의해 각 내용을 깃헙 액션 시크릿으로 부터 환경변수로 주입 받습니다.

#### c. 서버 통신 https 프로토콜로 변경
  - 2024.2.29 AWS 정책 변경으로 인해 ec2를 제외한 퍼블릭 ipv4 주소 사용 시 과금이 되어 로드밸런서 사용을 중지하게 됨으로 직접 종단간 https 프로토콜로 통신할 수 있도록 구현했습니다.
  - aws ec2 내부에서 certbot을 설치한 다음 Let's Encrypt를 통해 SSL/TLS 통신을 위한 무료 인증서를 발급 받았습니다.
  - 발급 시 사용된 도메인은 server.salog.kro.kr 입니다.
  - PEM 형식의 인증서를 java에서 직접 사용할 수 있도록 openssl 명령어를 사용하여 KeyStore 형식으로 변환했습니다.
  - 이후 /home/ec2-user 디렉토리에 저장된 KeyStore.p12 파일을 컨테이너 내부로 불러들일 수 없는 문제가 발생하여 컨테이너 실행 시 -v 옵션을 사용하여 호스트 시스템의 파일을 컨테이너 내부의 /app 디렉토리에 마운트했습니다.
  - 환경변수를 통해 애플리케이션 설정 파일(application.yml)에 위치, PW 등을 추가해 인증서를 연결했습니다.
  - 추가적으로 SecurityConfig 클래스를 구현하여 http 프로토콜로 요청을 받은 경우 https 프로토콜로 리다이렉션할 수 있도록 구현했습니다.

#### d. 에러 핸들링
  - GlobalExceptionAdvice AOP를 통해 고정적으로 발생할 수 있는 에러를 6개로 분기하여 처리했습니다.
  - 이외에도 Business 로직 중 나타나는 특정한 에러들을 상세히 응답하기 위해 Runtime Exception을 상속 받은 BusinessLogicException 클래스를 구현했습니다.
  - 이 클래스를 통해 서비스 로직 중 발생하는 에러는 커스텀 ExceptionCode 클래스를 활용하여 20개 이상으로 분기, 상세히 응답합니다.

#### e. 보안 설정
  - 클라이언트 측과 협업 중 CORS 에러를 피하기 위해 CorsConfigurationSource를 구현한 CustomCorsConfiguration 클래스를 구현했습니다.
  - 프론트엔드 개발 URL과 클라우트 프론트 URL을 바탕으로 오리진을 허용합니다.
  - WebMvcConfigurer을 구현한 SecurityConfiguration 클래스에서 각 URL에 대한 접근을 처리합니다.

#### f. DB 설계 변경
  - 기존에는 회원 테이블만 생성 시간을 created_at 으로 저장했지만 이제 모든 테이블에 적용하였습니다.
  - 적용되어 있지 않던 모든 엔티티 클래스에 Audit 클래스를 상속 받도록 변경하고, 생성-저장 시 생성 시간이 함께 저장됩니다.

<br>

### 4. 테스트
  - 전체 테스트 완료 후 로컬에서 깃헙 레포로 push 시 전체 테스트 실행, 통과하지 않으면 push가 실패하도록 스크립트를 작성했습니다.

#### a. 담당 도메인 전체 테스트
  - 컨트롤러에 대한 슬라이스 테스트를 진행하여 정상적인 API 통신이 가능한지 확인했습니다.
  - DB 연산이 예상대로 동작하는 지 확인하기 위해 레이어를 분리하여 슬라이스 테스트를 진행하여 검증했습니다.
  - 서비스 레이어의 모든 메서드가 정상적으로 동작하는 지 확인하기 위해 간접적인 private 메서드 테스트를 포함하여 전 메서드에 대한 유닛 테스트를 진행했습니다.
  - 각 도메인에 맞춰 전체적인 통합 테스트를 완료 했으며 IntelliJ의 테스트 커버리지 검사 기능을 활용하여 전 항목에 대해 85% 이상 커버하도록 테스트 케이스를 구현했습니다.

### b. 통합 테스트 성능 향상
  - 테스트 진행 시 beforeEach 로 목업 데이터를 생성함에도 불구하고 DB 식별자 생성 전략이 우선 시 되어 id가 중첩해서 증가하는 문제를 @DirtiesContext(methodMode = DirtiesContext.MethodMode.BEFORE_METHOD) 어노테이션으로 테스트 메서드 시작 전에 컨텍스트를 리로드하는 방식으로 해결했었습니다.
  - 이후 단순히 jdbcTemplate 라이브러리를 활용하여 직접적으로 쿼리를 입력해 매 메서드 시작 전 id가 1부터 시작하도록 변경하였습니다.
  - 해당 방법으로 수정 후 전체 테스트 시간이 10초 -> 3초로 크게 단축할 수 있었습니다.

#### c. 통합 테스트 후 API 문서화
  - 담당한 도메인들에 대한 통합 테스트를 진행한 후 보다 원활한 협업을 위해 API 문서 작성을 자동화 했습니다.
  - Asciidoctor 를 사용하여 전체 테스트 빌드 시 자동적으로 각 도메인에 맞는 디렉토리로 스니펫을 생성, 저장하여 문서를 자동적으로 생성할 수 있도록 구성했습니다.

<br>

### 5. 모니터링
#### a. 부하 테스트와 모니터링
  - JMeter 를 활용하여 로컬 환경에서 5분 이내로 100000 번의 조회 요청을 모의하여 부하 테스트를 진행했습니다.
  - 원활한 모니터링을 위해 프로메테우스를 사용하여 메트릭을 수집하고, 원활한 협업과 유지보수를 위해 그라파나로 수집된 메트릭을 시각화 했습니다.

<br>
<br>
<br>

## 💻 모니터링
  - 각종 테스트, 특히 대규모 트래픽 상황을 가정한 스트레스 테스트 시 원활한 확인을 위해 모니터링 도구를 사용했습니다.
  - 대규모 트래픽 시나리오는 JMeter 를 활용하여 모의했습니다.
  - 모든 내용은 로컬 테스트 환경에서 진행되었습니다.
  - JMeter 사용과 관련된 자세한 내용은 제 [블로그](https://021skyfall.github.io/posts/salog_project_test9/)에 기록되어 있습니다.
  - 프로메테우스와 그라파나의 적용 과정은 제 [블로그](https://021skyfall.github.io/posts/salog_project_test10/)에 기록되어 있습니다.

### 1. 프로메테우스 적용
  - 메트릭 수집을 위해 프로메테우스를 사용했습니다.
  - 애플리케이션의 빌드 파일과 설정 파일을 수정하여 프로메테우스와 연결, actuator로 메트릭을 수집하고 수집된 메트릭을 특정 api로 보낼 수 있도록 설정하였습니다.

![](https://private-user-images.githubusercontent.com/119563406/344874223-b7f6474a-edfe-4110-9e6d-40b329ad7d79.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk4OTQxMTMsIm5iZiI6MTcxOTg5MzgxMywicGF0aCI6Ii8xMTk1NjM0MDYvMzQ0ODc0MjIzLWI3ZjY0NzRhLWVkZmUtNDExMC05ZTZkLTQwYjMyOWFkN2Q3OS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNzAyJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDcwMlQwNDE2NTNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wOTQ0NTRkOTdiMjZjYThmMTE4N2Y4Zjk4OTdhOTZiYzk0NGFiZmExMzlkYjEzYTg1MjliZTIzMmY0NGNkZGJmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.DP2qM1rplHKlAZLso1FYyKG7x7n_REU-X6RyehenVcg)

<br>

### 2. 시각화를 위해 그라파나 적용
  - 텍스트로 수집된 메트릭을 모니터링하는 것은 불편하다고 생각되며, 협업을 위해 시각화를 결정했습니다.
  - 도구는 그라파나를 사용했으며 프로메테우스와 연결하여 주요 지표를 시각화 했습니다.
  - 생성된 패널은 아래와 같습니다.

![](https://private-user-images.githubusercontent.com/119563406/344874225-3cf05487-3dfc-420d-8e08-cb42b048b8d1.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk4OTQxMTMsIm5iZiI6MTcxOTg5MzgxMywicGF0aCI6Ii8xMTk1NjM0MDYvMzQ0ODc0MjI1LTNjZjA1NDg3LTNkZmMtNDIwZC04ZTA4LWNiNDJiMDQ4YjhkMS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNzAyJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDcwMlQwNDE2NTNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00ZmRmYzI1M2RiYjZkMWU3NWVmN2I4MjUxMzQ4MDZhNWM1NGI3OWRhMmIzNmJkMDA1MDI0ZTk3ODgzNDlkMzA5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.ZL1RXN64NpLafKVcFZwkPI1lWAi94RVy1DdlphqsXbY)


<br />
<br />

## 🖥️ 페이지 별 기능 

### [초기화면]
- 웹서비스 접속 초기화면으로 AOS(Animate on scroll)가 적용 되어있습니다.
    - 로그인이 되어 있지 않은 경우에만 접근 가능합니다.

| 초기화면 |
|----------|
|![2024-03-083 49 55-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/Salog/assets/120611048/9845e1ed-a2ae-4e90-bec9-42eab7c0e0fd)|

<br />
<br />

### [회원가입]
- 이메일 주소와 비밀번호를 입력할 때, 입력창에서 벗어나면 유효성 검사가 진행되고 통과하지 못한 경우 각 경고 문구가 입력창 하단에 표시됩니다.
- 이메일 주소의 형식이 유효하지 않으면 인증 버튼이 활성화되지 않으며, 이미 가입된 이메일일 경우 인증 버튼 클릭 시 입력창 하단에 경구 문구가 나타납니다.
- 작성한 이메일을 통하여 인증번호를 받아 입력하는 검증 과정을 거쳐야합니다.
- 작성이 완료된 후, 유효성 검사가 모두 통과되면 회원가입 버튼이 활성화되며, 버튼을 클릭하면 회원가입이 완료되어 로그인 페이지로 이동됩니다.

| 유효성 검사 | 이메일 인증 |
|:---:|:---:|
|![2024-03-024 04 19-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/salog/assets/120611048/69b4fd70-7ff5-4c92-b7e1-873d57e36f10)|![2024-03-024 12 35-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/salog/assets/120611048/bcca3976-0b0e-4019-9ea7-5ccef39445f9)|

| 회원가입 |
|----------|
|![2024-03-024 17 18-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/salog/assets/120611048/8c23808e-1636-435c-a717-4c2aeab5eb9b)|

<br />
<br />

### [로그인]
- 이메일과 비밀번호를 입력하여 로그인을 진행합니다.
   - 로그인 버튼 클릭 시 입력값이 일치하지 않을 경우에는 경구 문구가 나타나며,
로그인에 성공하면 홈 대시보드 화면으로 이동합니다.
- 소셜 로그인(카카오, 구글, 네이버)을 통한 서비스 이용이 가능합니다. (현재는 구글만 가능)

| 일반 로그인 | 소셜 로그인(구글) |
|:---:|:---:|
|![2024-03-024 22 24-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/salog/assets/120611048/b735f71a-3ed7-41b6-85e6-e500254a6b0a)|![2024-03-024 41 20-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/salog/assets/120611048/a9751450-1431-4c6a-9c2a-42a1188bb80e)|

<br>

### [비밀번호 찾기]
- 비밀번호를 잊어버렸을 때, 로그인 페이지에서 하단에 있는 비밀번호를 찾기를 진행합니다.
- 이메일을 입력하여 인증번호를 받고, 인증이 완료되면 비밀번호를 재설정할 수 있습니다.

| 비밀번호 찾기 |
|----------|
|![2024-03-024 56 25-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/salog/assets/120611048/9e4d40b6-c4cd-4058-a8f4-46b9050bcfbb)|

<br>

### [비밀번호 변경 & 회원 탈퇴]
- 기존 비밀번호, 새로운 비밀번호를 입력하여 비밀번호를 변경할 수 있습니다.
- 회원 탈퇴를 한 뒤, 해당 계정으로 재가입이 가능합니다.
- 설정 페이지에서 해당 기능들을 사용할 수 있습니다.

| 비밀번호 변경 | 회원 탈퇴 |
|:---:|:---:|
|![2024-03-158 59 10-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/Salog/assets/120611048/7ded3643-a0ae-41ad-9e94-075dae104f4b)|![2024-03-159 02 38-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/Salog/assets/120611048/e02657b5-9acc-46ec-9559-cc5c34978ff0)|

<br>

### [로그아웃]
- 좌측의 sidebar에 있는 로그아웃을 클릭 후 나타나는 모달창의 확인 버튼을 클릭하면 로그아웃이 됩니다.
- 로그아웃시 로컬 저장소 및 쿠키의 토큰 값을 삭제하고 로그인 화면으로 이동합니다.

| 로그아웃 |
|----------|
|![2024-03-025 06 34-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/salog/assets/120611048/8942f28e-8bb8-4594-9953-13d88d10a77c)|

<br>

### [대시보드]
- 이번 달 지출 · 수입 · 낭비리스트 · 예산을 그래프와 함께 확인할 수 있습니다.
- 하단의 캘린더는 타일마다 해당 일의 지출과 수입의 합계를 보여주며, 타일을 클릭하면 작성 된 가계부를 조회할 수 있습니다.
- 타일에 마우스를 올리면 작성 아이콘이 보여지며, 클릭 시 가계부를 작성할 수 있습니다.

| 대시보드 |
|:---:|
|![2024-03-026 01 12-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/salog/assets/120611048/38793435-ea5c-4a8c-b66d-3ef08c33d218)|

<br>

### [지출 · 수입]
#### 1. 지출 · 수입 조회
- 상단의 탭을 통하여 지출과 수입을 따로 볼수 있으며, 낭비리스트를 확인할 수 있습니다.
- 낭비리스트는 지출내역 중 추가할 수 있으며, 항목을 체크하면 나오는 탭에서 낭비리스트 버튼으로 추가 가능합니다.
- 날짜 오름차순 / 내림차순 정렬이 가능하고 카테고리 필터링 및 특정 날짜 필터링 조회 기능이 추가 될 예정입니다.

| 지출 · 수입 조회 |
|:---:|
|![2024-03-026 24 43-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/salog/assets/120611048/dcadff14-9e9f-40d4-a4da-b531949eaea2)|

<br>

#### 2. 지출 · 수입 작성
- 가계부 작성하기 버튼을 클릭하면 작성 모달이 나옵니다.
- 주어진 항목들을 입력하면 작성 버튼이 활성화되어 가계부 작성이 가능합니다. (항목 중 메모는 작성하지 않아도 됩니다)
- 하단의 행 추가를 눌러 여러 개의 내역을 작성할 수 있습니다.

| 지출 · 수입 작성 |
|:---:|
|![2024-03-026 28 34-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/salog/assets/120611048/7ff77e6c-a7b5-4f28-8b50-2202c0bff827)|

<br>

#### 3. 지출 · 수입 수정 & 삭제
- 항목들을 체크하여 나오는 탭에서 수정 또는 삭제를 클릭합니다.
- 수정 및 삭제로 인해 내용이 변경되면 페이지에 바로 반영됩니다.

| 지출 · 수입 수정 & 삭제 |
|:---:|
|![2024-03-026 49 33-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/salog/assets/120611048/1248e98c-d420-4aed-84ec-c3771c413197)|

<br>

### [분석]
- 이번 달 지출을 차트 및 그래프를 통해 분석을 보여주는 페이지입니다.
- 최근 3개월 지출 합계, 주간 별 분석, 분류 별 지출, 예산 소진율, 낭비 리스트를 확인할 수 있습니다.

| 분석 |
|:---:|
|<img width="610" height="310" alt="스크린샷 2024-03-02 오후 8 28 25" src="https://github.com/kimtjrgus/salog/assets/120611048/e14c09c8-120f-435c-bf03-3bd931445433">|

<br>

### [예산]
- 이번 달 예산을 설정하고 남은 예산 및 하루 예산을 볼 수 있습니다.

| 예산 |
|:---:|
|![2024-03-027 08 26-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/salog/assets/120611048/fbfce4be-6114-4fdb-974a-129a9ea04b18)|

<br>

### [고정 지출 · 수입]

#### 1. 고정 지출 · 수입 조회
- 달마다 고정으로 발생하는 지출 및 수입을 관리하는 페이지입니다.
- 고정 지출은 지출 일을 기준으로 3일 미만 남았다면 빨간색, 일주일 미만이면 노란색, 일주일 이상은 초록색으로 표시됩니다.

| 고정 지출 · 수입 조회 |
|:---:|
|<img width="610" height="312" alt="스크린샷 2024-03-02 오후 8 36 56" src="https://github.com/kimtjrgus/salog/assets/120611048/7c6fd232-8df7-4d39-ad63-8ccc45d9fc8b">|

<br>

#### 2. 고정 지출 · 수입 작성
- 항목들을 작성하면 일정 추가하기 버튼이 활성화됩니다.

| 고정 지출 · 수입 작성 |
|:---:|
|![2024-03-027 21 07-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/salog/assets/120611048/e77aff03-a61f-4569-acef-a557f7fbdaf0)|

<br>

#### 3. 고정 지출 · 수입 수정 & 삭제
- 상단의 탭을 통하여 일정 수정 탭으로 이동하면 수정 및 삭제가 가능합니다.
- 금융 일정 목록에서 수정하고 싶은 항목을 선택하여 내용 수정을 할 수 있습니다.
- 목록 하단의 삭제하기를 클릭하여 내용 삭제를 할 수 있습니다.

| 고정 지출 · 수입 수정 & 삭제 |
|:---:|
|![2024-03-027 26 13-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/salog/assets/120611048/0b2fb1ed-64b8-4148-95ca-52449ff7b031)|

<br>

### [영수증 인식]
- 영수증의 가계 이름, 지출 일, 총 합계의 항목을 인식하여 가계부를 작성할 수 있습니다.
- 영수증 인식을 통하여 가계부를 작성하면 가계부 조회 시 영수증 사진을 볼 수 있습니다.
- 대시보드 페이지, 지출&수입 페이지에서 가계부를 작성할 때 사용 가능합니다.
- 이미지 업로드 -> 영수증 인식 -> 내용 확인 -> 자동작성의 플로우를 가집니다.

| 영수증 인식(대시보드 페이지) | 영수증 인식(지출&수입 페이지) |
|:---:|:---:|
|![2024-03-159 13 28-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/Salog/assets/120611048/4399bb91-b6a4-47d9-ac69-49ff0df71766)|![2024-03-159 16 49-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/Salog/assets/120611048/813f0f05-cb88-4bc2-9db8-7565155d8b8a)|

<br>

### [알림]
- 웹 알림이 있습니다.
  - 웹 알림은 헤더의 알림 아이콘을 클릭하여 확인 가능하며, 알람을 확인 후 삭제하면 로컬 저장소에 저장되어 알림이 다시 발송되지 않습니다. 
- 고정 지출 및 수입에서 일정이 3일 미만인 항목들만 알림을 발송하며, 일정 당일날에는 해당 목록들을 가계부에 추가하는 것을 묻는 모달을 보여줍니다.
- 알림 설정은 회원 가입 시 가능하며, 헤더의 알림 아이콘을 클릭하면 하단의 스위치를 통하여 on/off 가능합니다.

| 알림 |
|:---:|
|![2024-03-027 54 16-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/salog/assets/120611048/70567a95-d9fe-403d-8795-58aa2adbe727)|

<br>

### [일기]
#### 1. 일기 전체 조회
- 작성한 모든 일기를 조회하는 페이지입니다.
- 제목으로 검색, 태그 필더링 및 날짜 필터링 조회가 가능합니다.

| 일기 전체 조회 |
|:---:|
|![2024-03-028 53 52-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/salog/assets/120611048/344b9303-2ab5-44ad-bc57-aa28d9f142bd)|

<br>

#### 2. 일기 상세 조회
- 전체 조회 페이지에서 일기를 선택하여 조회합니다.
- 텍스트 에디터로 작성 된 일기가 그대로 보여지며, 우측에는 일기를 작성한 당일의 가계부를 확인할 수 있습니다.

| 일기 상세 조회 |
|:---:|
|<img width="610" height="312" alt="스크린샷 2024-03-02 오후 9 25 27" src="https://github.com/kimtjrgus/salog/assets/120611048/d0a29a8e-b285-4e7c-98b5-26f0d9ae7b97">|

<br>

#### 3. 일기 작성
- 텍스트 에디터를 통하여 본문에 이미지를 첨부할 수 있습니다.
- 우측에는 작성 당일의 가계부가 표시되어 내역을 볼 수 있습니다.
- 작성 버튼을 누르면 유효성 검사가 진행되고 통과하지 못하면 토스트 창으로 경고 문구가 나타납니다.
- 작성이 완료되면 전체 조회 페이지로 이동합니다. 또한 본문의 이미지를 올렸다면 썸네일로 지정하며,
  이미지가 여러개라면 첫 번째를 썸네일로 지정하여 전체 조회에 보여집니다.

| 일기 작성 |
|:---:|
|![2024-03-029 12 21-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/salog/assets/120611048/6c72940c-248a-4384-b209-cc17fd4b9fd4)|

<br>

#### 4. 일기 수정 & 삭제
- 일기 상세 조회시 상단의 수정 및 삭제 버튼을 클릭합니다.
- 수정 또는 삭제가 완료되면 전체 조회 페이지로 이동합니다.

| 일기 수정 & 삭제 |
|:---:|
|![2024-03-029 21 13-ezgif com-video-to-gif-converter](https://github.com/kimtjrgus/salog/assets/120611048/c3cb819c-f062-4670-9b25-f5c555604c06)|

<br />
<br />

## 🎆 개선 목표

### 1. 테스트 케이스 - 완료
- 단위 테스트로 진행
- 테스트 케이스 작성 완료 후 API 문서화

<br>

### 2. 보안 - 완료
- 이메일이 연락 가능한지 체크가 안된 상태로 가입 시도 시 에러 처리
- 리프레쉬 토큰을 활용한 jwt 재발급 삭제 후 토큰 만료시간 짧게 설정 및 토큰 자동 갱신 방식 사용

<br>

### 3. 성능 최적화 - 테스트, 모니터링 완료
- JMeter 부하 테스트 시도 후 최적화
- 그라파나 모니터링 시도 후 최적화

<br>

### 4. 클린코드 - 소나린트를 활용하여 개선 완료
- Prettier를 활용하여 일관된 스타일의 코드로 변경
- PMD를 활용하여 불필요한 요소 제거

<br>
<br>
<br>

## 📢 피드백
- 일반 사용자 32명의 피드백
- 긍정적인 피드백, 중복 피드백 제외
- 수용가능한 피드백만 작성
- 각 항목 하단에 진행 결과 작성(==>)

```
1. 수입/지출 작성 중 버튼 활성화 안되는게 비직관적임 << 왜 활성화 안되는지 모르겠음
-> 일단 눌리되 작성 완료 안 되어있으면 알림 띄우는게 좋아보임
-> 회원 가입 쪽도 마찬가지로 빈 데 있으면 버튼 눌렀을 시 빈 곳 알림
=> 수입/지출 작성 & 회원가입 동작 버튼 활성화하고 눌렀을 때 작성 안되는 이유 알림
==> 작성 완료 버튼은 항상 활성화, 작성에 대한 힌트 표시로 해결 완료

2. 영수증 스캔 있는데 왜 안됨?
-> 아예 안 보이게 하든지 계정 새로 넣던지 해야할듯
=> 네이버 OCR 계정 새로 생성해서 동작 시키도록 변경
==> 신용카드 등록으로 인해 담당자 해결중

3. 낭비 리스트 직관적이지 않다 < 딱 보면 뭔지 모르겟음 < 딱 눈에 기능이 안 들어옴
=> 지출/수입 에서 낭비리스트 옆에 "?" 표시 넣고 간단한 설명 추가
==> 멘트 지정 완료, 프론트 측 해결중

4. SEO 작업
=> 구글 완료, 네이버는 가능하면 진행
==> 피드백 이전에 완료된 작업

5. 지출/수입 에서 특정 날짜를 선택할 수 있는 기능
=> 추가 예정이나, API 확인 후 필요시 백엔드에 요청
==> 새로운 기능 구현으로 해결 완료

6. 앱으로 출시 할 생각은 없는지 (모바일 뷰)
=>  오래 걸릴 예정이여서 우선순위 낮음 (다른 내용 완료한 뒤 다시 협의)
==> 하이브리드 앱으로 패키징을 위해 프론트 측과 협의중

7. 카테고리, 결제수단이 커스텀되었으면 좋겠다,
=> 카테고리는 XX 메모로 쓸 것 , 결제수단은 커스텀할 수 있게 조치
==> 카테고리와 결제수단은 문자열로 통신하며 개인 별로 작성할 수 있도록 변경 완료

8. 설정에 계정 연동타입이 표기되었으면 좋겠다
=> 소셜 로그인 회원 조회 시 소셜 타입 컬럼값 추가
=> 해당 값을 바탕으로 설정 창에서 [비밀번호 변경] 항목 숨김 처리 및 계정 아이콘 해당 소셜 아이콘으로 변경
==> 회원의 social_type 컬럼을 추가, 로그인 후 회원 조회 시 소셜 로그인 아이콘 노출로 변경 완료

+ DB에 회원 말고는 createdAt으로 생성 시간을 표시하지 않는 이유가 있나?
=> 이유가 없다. 사실 생각 조차 안했다.
=> 당연히 추후 로깅 작업을 하기 위해서는 DB에 모든 데이터는 생성 시간이 표시되어야 한다.
=> DB 설계를 수정할 예정
==> 모든 엔티티가 Audit 클래스를 상속 받도록 변경, 생성 시간을 저장하도록 변경 완료

9. 지정 카테고리 커스텀
=> 메모를 사용하게 끔 유도한 시스템이지만 요청이 많아, 문자열로 카테고리 직접 기입 가능하게 끔 수정
==> 7번 항목과 동일

10. 처음 이용하는 사람들을 위한 FAQ나 이용방법이 설명되어있으면 좋겠음
=> 1차 피드백에서도 나왔던 얘기인데, 이 번에는 전반적인 기능에 대한 설명이 필요한 것으로 보임
=> 기능 옆에 물음표로 표기해서 사용법이 뭔지 글로 표시
==> 3번 항목과 동일

11. 원화 뿐만이 아니라 외화도 허용해주었으면 함
(외화벌이의 경우나 외국주식시장을 이용하는 고객타겟)
=> 이는 샐로그 기획 당시에는 주 타겟이 이쪽이 아니었기 때문에 추가될 가능성은 낮지만 인지는 하고 있음

12. 주식시장 동향 api를 가져올 수 있으면 활용해서 보여주면 괜찮을 것 같다
(다양하면 더 좋겠지만 코스닥이나 환율시세 정도만)
=> api 활용에 대해서는 긍정적, 다른 주요 주제 추가 후 고려
==> 우선 순위는 낮으나 프론트 측의 작업이 끝나는 대로 적용 예정

13. 분석 시 지난달 3개월뿐만 아니고 1년까지도 나왔으면 좋겠음
=> 기존 분석 파트 통계에서는 3개월 간의 지출만 출력됨
=> 수익, 지출 포함하여 3개월이 아닌 1년으로 확장
==> 기존 지출 통계 뿐만 아니라 수입을 포함하여 3개월이 아닌 1년 노출로 변경 완료

14. 일기가 오늘 날짜 밖에 안되는 것이 불편하다.
=> 날짜를 수정할 수 있도록 변경함
==> 일기의 날짜 수정이 가능하도록 변경 완료

15. 가계부 작성 시 디폴트로 오늘 날짜가 미리 셋팅 되어 있으면 좋겠다.
=> 수입, 지출 작성 시 당일 날짜로 자동 지정되도록 수정함
==> 해결 완료

16. 가계부 작성, 금액 입력시 원화 구분점이 표기되었으면 한다.
(2000000 >> 2,000,000)
=> 작성 완료 후에는 쉼표 구분점이 출력되지만, 작성 중에는 표시가 없어 불편함
=> 작성 중에도 표시 가능하도록 변경
==> 해결 완료

17. 대시보드, 분석에도 원화 단위 구분점이 필요
=> 대시보드와 분석에서 원화 구분점이 표시가 안되는 문제 해결
==> 해결 완료

18. 카테고리별 예산 설정 세분화
=> 현재는 통합 예산으로 설정되어 있지만, 카테고리 별로 예산 설정을 세분화 하고 싶다는 피드백임
(ex. 식비 예산, 의류 예산 등)
==> 화면 구성부터 다시 생각해야하기 때문에 프론트 측 업무가 완료되면 다시 의논해볼 것

19. 1년 - 10년 단위 장기적인 목표 금액 설정과 함께 연봉 등을 입력해서 한달, 
혹은 1년에 얼마씩 모아야하는지 계산해주는 계산기 기능도 있으면 좋겠다.
=> 예산과는 별개로 '목표 금액'을 지정하고서 해당 금액을 채우기 위해 단위 날짜 별로 얼마를 모아야 목표 금액에 도달할 수 있는 지 계산 하는 기능
==> 추가 예정, 이 기능에 대한 이름 고민 중..

20. 처음 로그인 후 자동 로그인
=> 세션에 정보를 저장한 후 로그인 시 이를 활용하여 자동적으로 로그인 할 있도록 토글 추가함
==> 해결 완료

21. 로그인 시 이메일/비밀번호 입력 후 키보드 엔터 누르면 다음 화면으로 넘어 가는 기능
=> 마우스 사용 없이 키보드만으로 엔터 입력하면 로그인 되게 끔 수정함
==> 해결 완료

22. 지출/수입 카테고리 좀 더 세분화
예를 들어 의류, 뷰티는 쇼핑으로 묶고 메모에 쓰면 되지 않나
=> 이전에 계속 나왔던 카테고리 커스텀에 관련된 내용
=> 이 피드백은 오히려 카테고리 개수를 늘리고 메모에 상세 내용 적으면 될 것 같다고 함
=> 여러 번 비슷한 피드백을 받았지만 사용자 마다 생각하는 게 달라서 카테고리 쪽은 커스텀만 추가 하는걸로 결정
==> 7, 9 번 항목과 동일 => 여러번 나오는 피드백인데, 그만큼 의견이 갈리는 것을 보여주기 위해 작성함

23. 지출/수입 작성 시에 아래 공백 부분에 작성 방법에 대한 설명이나 예시가 있으면 좋을 거 같다
=> 가계부 작성하기 우측에 물음표로 간단한 설명
=> 필수 항목 어떤 게 있는 지, 입력 순서(분류를 먼저 입력하셔야 카테고리가 열립니다 등) / 우리만 알 수 있는거 등등
==> 3, 10 번 항목과 동일 => 여러번 나오는 피드백인데, 그만큼 중요하다는 것을 보여주기 위해 작성함

24. 일기 10자 제한 해제
=> 도배 방지용 이었는데, 개인 일기라 없애도록 함
==> 해결 완료

25. 일기 쪽 작성 시 오른쪽에 "작성한 가계부" 아무 내용이 안나옴
=> 일기 작성 시 당일 가계부가 출력되는 데, 애매한 제목 때문에 인지를 못한 듯 함
=> 우측에 출력되는 가계부 이름을 좀 더 명확히 설정함
==> 일기 작성 시 노출되는 가계부의 명칭을 직관적으로 변경함으로 해결 완료

26. 일기 작성 시 파일 첨부 가능한지
=> 가능하게 변경할 예정
=> 다만, 에디터를 사용하는 것이기 때문에 프론트 측에서 진행해본 다음 백으로 어떻게 파일을 보내는 지 알아야 함
=> 용량 제한 필수 조건
==> 진행 중

27. 대시보드 캘린더 클릭하면 수입/지출 내역 뿐만 아니라 일기도 간략하게 나오면 좋을거 같다
=> 대시보드에 일기가 노출되면 화면이 복잡할 것이라고 생각됨
=> 대안으로 대시 보드 캘린터 세부 조회 자체에는 노출 안되지만, 해당 날짜 일기로 이동하는 버튼 생성
=> 해당 버튼 누르면 일기 페이지로 이동, 당일 날짜 일기 리스트 노출하도록 변경
=> 단, 일기 세부 조회 아니고 리스트가 노출될 것
==> 일기 리스트 노출로 해결 완료

28. 일기 쪽에서 검색 시 제목 말고 내용으로도 검색 가능하면 좋을 거 같음
=> 동시 검색 말고(복잡해지니까) 두 가지 검색 기능이 있어야 할 거 같음
=> 토글로 변경해서 제목만 검색 / 내용만 검색 / 제목+내용 검색 세 가지로 분리해서 검색할 수 있도록 수정함
==> 내용, 제목+내용 검색 기능 추가 완료
```

<br>
<br>
<br>
 
## 🎉 프로젝트 후기

### 이용석
이번 프로젝트는 이전에 진행했던 경험을 바탕으로 팀을 구성하여 더욱 발전된 결과물을 만들어낼 수 있었습니다. 
개개인의 시간을 활용하여 진행된 프로젝트였기에 일정은 예상보다 조금 늘어났지만, 그만큼 더 깊고 세밀한 부분까지 고려할 수 있었습니다.

특히, 보안과 배포 환경에 대한 깊은 고찰을 할 수 있던 시간은 매우 값진 경험이었습니다. 
이런 과정에서 Oauth와 Docker 같은 새로운 기술을 접하면서 통신 프로토콜과 배포 방법에 대한 이해도 깊어졌습니다. 
이 과정에서는 어려움도 많았지만, 그 어려움을 극복하며 새로운 기술을 습득한 것은 큰 성취감을 주었습니다.

에러 로그 분석 방법 등, 제 자신의 성장을 체감할 수 있는 순간도 있었습니다. 
프로젝트에 참여한 팀원들에게 감사의 마음을 전하며, 앞으로 리펙토링을 통해 이 프로젝트를 완벽에 더 가까이 가져가고자 합니다.

### 김석현
부트캠프 때 배웠던 것을 복습하는 느낌으로 팀원과 다 같이 설계부터 
프로젝트 끝까지 다시 구현해본 뜻 깊은 시간이었습니다.
지난 프로젝트때를 기억하며, 이번 프로젝트를 시작했었고 어떤 부분이 부족했는지,
더 채워나갈 부분은 무엇인지 알고 협업하며 공부하는 것이 재밌었습니다.

저는 백엔드로써 AWS를 다루고 배포하는 것에 대해 부족하다고 느꼈는데,
좀더 익숙해지고 Docker, Clova Api 등을 다루며, 이전에는 못 해보았던 것들을 경험하고 한 층 더 성장한 것 같습니다. 
트러블슈팅의 순간순간을 기록하지 못해 조금 아쉬운 점이 있으나, 일부 기록하고 차후에 블로깅을 하며 되새기는 것도 
하나의 재미일 것 같아 두근거립니다.
그리고 앞으로도 해당 프로젝트에 새로 배운 기술들의 추가나 좀 더 클린한 코드, 클린한 아키텍처로 
리팩토링하며 더 좋은 프로젝트가 되도록 가다듬어 보려합니다.

함께 협업한 코드마우스팀, 용석님 유준님 감사합니다.

### 선유준
많은 것을 배울 수 있었던 프로젝트였습니다. 
프론트엔드를 혼자 담당하게 되어 기획한 모든 기능들을 구현 해내기 위해 노력하였으며, 점차 완성되어 가는 웹을 보며 뿌듯함을 느꼈습니다.

기능적 부분으로는 Redux-toolkit을 사용하면서 리덕스 상태를 지속적으로 저장 및 복원하기 위한 Redux-persist를 사용하면서 전역상태를 사용해보는 경험을 해본 점이 좋았습니다.
추가로, 텍스트 에디터를 사용하여 이미지를 올릴 때 base64 형식으로 인코딩되어 저장되는 것을 firebase storage를 사용하여 url로 변환하여 사용하는 과정으로 최적화도 이뤄냈고, 가독성 문제도
해결한 뿌듯한 성과를 이뤄내며 성장할 수 있었습니다.

아쉬운 점으로는 React의 상태를 관리하면서 서버와 통신 할 때 최신화하는 것을 위해 React-Query를 사용해보고 싶었지만, 기능을 구현하는 것에 초점을 두어 학습하지 못한 점이 아쉬웠습니다.

모두 고생하셨고 리팩토링을 통하여 더 나은 프로젝트 완성까지 화이팅해봅시다!
