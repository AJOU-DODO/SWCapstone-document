<p align="center">
  <img src="https://github.com/user-attachments/assets/4ad9e822-e3ff-446c-890a-df8293ee6a16" alt="dodo logo" width="128" />
</p>

<h1 align="center">DODO JOURNEY</h1>

<p align="center">
  <strong>산책을 탐험으로 바꾸는 위치 인증 기반 로컬 커뮤니티<br/>
  <em>Walk. Verify. Explore.</em>
</p>

# 📂 Repositories

| Part | Link | Description |
| :--- | :--- | :--- |
| **Backend** | [![Backend](https://img.shields.io/badge/Backend-6DB33F?style=for-the-badge)](https://github.com/AJOU-DODO/SWCapstone-backend) | Spring Boot 기반 API 서버 및 인프라 설정 |
| **Android** | [![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge)](https://github.com/AJOU-DODO/SWCapstone-android) | 안드로이드 네이티브 앱 소스 코드 |
| **Frontend** | [![Frontend](https://img.shields.io/badge/Frontend-61DAFB?style=for-the-badge&logoColor=black)](https://github.com/AJOU-DODO/SWCapstone-frontend) | 프론트엔드 웹 & 웹뷰 소스 코드 |
| **Document** | [![Document](https://img.shields.io/badge/Document-181717?style=for-the-badge)](https://github.com/AJOU-DODO/SWCapstone-document) | 프로젝트 문서 및 설계 자료 (docx, pdf) |

---

# 👥 Team Members (TEAM DODO)

| 프로필 | 이름 | 담당 | 이메일 | GitHub |
| :---: | :---: | :---: | :---: | :---: |
| <img src="https://github.com/kando0330.png" width="80"> | **한도훈** (팀장) | Infrastructure & Backend | [gks9315@ajou.ac.kr](mailto:gks9315@ajou.ac.kr) | [![GitHub](https://img.shields.io/badge/github-121013?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kando0330) |
| <img src="https://github.com/apdlwjwjwj.png" width="80"> | **채승우** | Android Native | [apdlwjwjwj@ajou.ac.kr](mailto:apdlwjwjwj@ajou.ac.kr) | [![GitHub](https://img.shields.io/badge/github-121013?style=for-the-badge&logo=github&logoColor=white)](https://github.com/apdlwjwjwj) |
| <img src="https://github.com/defhoon.png" width="80"> | **정의훈** | Frontend | [twilight22@ajou.ac.kr](mailto:twilight22@ajou.ac.kr) | [![GitHub](https://img.shields.io/badge/github-121013?style=for-the-badge&logo=github&logoColor=white)](https://github.com/defhoon) |
| <img src="https://github.com/Rain-fore.png" width="80"> | **최환희** | Frontend | [choihh2660@ajou.ac.kr](mailto:choihh2660@ajou.ac.kr) | [![GitHub](https://img.shields.io/badge/github-121013?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rain-fore) |

---

# 목차  

- [📂 Repositories](#-repositories)
- [👥 Team Members (TEAM DODO)](#-team-members-team-dodo)
- [목차](#목차)
- [서비스 개요](#서비스-개요)
- [서비스 상세 소개 (메뉴얼/튜토리얼)](#서비스-상세-소개-메뉴얼튜토리얼)
  - [산책가\&기록가 (일반 유저)](#산책가기록가-일반-유저)
    - [첫 화면](#첫-화면)
    - [둥지 찾아가기 및 해금](#둥지-찾아가기-및-해금)
    - [둥지 확인](#둥지-확인)
    - [둥지 만들기](#둥지-만들기)
    - [설정 창](#설정-창)
    - [마이페이지](#마이페이지)
    - [문의사항 창](#문의사항-창)
  - [광고주 페이지](#광고주-페이지)
    - [광고주 대시보드](#광고주-대시보드)
    - [광고 신청 페이지](#광고-신청-페이지)
  - [관리자 페이지](#관리자-페이지)
    - [유저 관리](#유저-관리)
    - [둥지 관리](#둥지-관리)
    - [신고된 엽서](#신고된-엽서)
    - [카테고리 관리](#카테고리-관리)
    - [공지사항](#공지사항)
    - [통계확인](#통계확인)
    - [문의사항](#문의사항)
    - [광고관리](#광고관리)
- [설계 및 구현](#설계-및-구현)
  - [소프트웨어 아키텍처](#소프트웨어-아키텍처)
    - [🧱 시스템 컴포넌트별 상세 설계](#-시스템-컴포넌트별-상세-설계)
      - [클라이언트 레이어 (Client Layer)](#클라이언트-레이어-client-layer)
      - [인프라 및 애플리케이션 레이어 (Infrastructure \& Application Layer)](#인프라-및-애플리케이션-레이어-infrastructure--application-layer)
      - [데이터 및 스토리지 레이어 (Data \& Storage Layer)](#데이터-및-스토리지-레이어-data--storage-layer)
  - [ERD](#erd)
  - [Repository 구조](#repository-구조)
    - [BE](#be)
    - [FE](#fe)
    - [AN](#an)
  - [핵심 기술 스택](#핵심-기술-스택)
    - [BE](#be-1)
    - [FE](#fe-1)
    - [AN](#an-1)
  - [DevOps, 배포](#devops-배포)
    - [BE](#be-2)
    - [FE](#fe-2)
    - [AN](#an-2)
  - [테스트 정책](#테스트-정책)
    - [BE](#be-3)
    - [FE](#fe-3)
- [빌드 방법 (Build Instructions)](#빌드-방법-build-instructions)
  - [BE](#be-4)
  - [FE](#fe-4)
  - [AN](#an-3)
- [협업 규칙 (Collaboration Rules)](#협업-규칙-collaboration-rules)
  - [공통](#공통)
  - [BE](#be-5)
    - [백엔드 협업 및 코드 개발 규칙 가이드](#백엔드-협업-및-코드-개발-규칙-가이드)
    - [패키지 구조 및 도메인 개발 규칙](#패키지-구조-및-도메인-개발-규칙)
  - [FE](#fe-5)
    - [개발 및 코드 규칙 (Coding Standards)](#개발-및-코드-규칙-coding-standards)
    - [테스트 및 품질 관리 (Testing \& QA)](#테스트-및-품질-관리-testing--qa)
    - [문서화 및 보안 (Docs \& Security)](#문서화-및-보안-docs--security)
  - [AN](#an-4)
    - [개발 및 코드 규칙 (Coding Standards)](#개발-및-코드-규칙-coding-standards-1)
    - [테스트 및 품질 관리 (Testing \& QA)](#테스트-및-품질-관리-testing--qa-1)
    - [문서화 및 보안 (Docs \& Security)](#문서화-및-보안-docs--security-1)

# 서비스 개요

**DODO JOURNEY**는 단조로운 산책을 특별한 여정으로 바꾸는 위치 기반 로컬 커뮤니티 서비스입니다.

- **장소에 깃든 이야기, 둥지** : 흐릿한 블러와 프리뷰 너머 숨겨진 타인의 이야기가 호기심을 자극합니다.
- **발걸음으로 완성하는 인증** : 오직 그 장소에 물리적으로 도달해야만 실시간 GPS 검증을 통해 온전한 이야기가 해금됩니다.
- **다정한 익명 연결** : 감성적인 엽서 교환과 이모지 리액션 및 댓글 기능으로 익명성에 기반한 따듯하고 새로운 형태의 로컬 커뮤니티를 형성합니다.

# 서비스 상세 소개 (메뉴얼/튜토리얼)

***주의 사항***

1. 앱 특성상 위치 권한은 필수 입니다.
2. fake gps등 gps 조작 앱이 깔려 있을 경우 사용이 제한 될 수 있습니다.
3. 어떠한 방식으로든 gps를 조작할 경우 사용이 제한 될 수 있습니다. 


    

## 산책가&기록가 (일반 유저)

### 첫 화면
<img width="270" height="660" alt="image" src="https://github.com/user-attachments/assets/54cf0d20-e65a-4ebc-a02d-e5823d07208a" />


- 좌측 하단 버튼을 통해 둥지를 만들 수 있습니다. (글쓰기)
- 중앙 하단 버튼을 통해 화면의 지도를 현재 위치로 이동하고 주변 둥지를 최신화합니다.
- 우측 하단 버튼 클릭시 편의를 위한 다양한 메뉴를 볼 수 있습니다.
- 지도 위에 둥지들이 표시됩니다. 단일 둥지는 알 하나, 여러 둥지는 세 개의 알이 모여있습니다.
- 선물이 들어있는 둥지는 광고 둥지입니다.



### 둥지 찾아가기 및 해금

<img width="270" height="660" alt="image" src="https://github.com/user-attachments/assets/b71e2b44-f943-44f1-b3b8-68aa45ea1b55" />


<img width="270" height="660" alt="image" src="https://github.com/user-attachments/assets/cb79055e-9e5c-4bf0-8fcc-cb14c120dff6" />


- 궁금한 둥지를 클릭하면 블러된 내용의 둥지가 나타납니다.
- 둥지를 다시 선택하면 찾아가기 모드가 시작되며, 둥지까지의 직선 방향을 알려줍니다.
- 범위 내에 도착하면 알림이 도착하고, 둥지 해금이 가능합니다.
- 이제 블러되지 않은 온전한 둥지를 볼 수 있습니다.


### 둥지 확인

<img width="270" height="660" alt="image" src="https://github.com/user-attachments/assets/57a5cbc4-931c-49af-b3d2-2f850b8d487c" />

- 둥지에 대한 좋아요 및 댓글 작성이 가능합니다.
- 해당 둥지에 엽서가 있을 경우 미리 만들어둔 엽서와 교환이 가능합니다. (하루 최대 3번)



### 둥지 만들기

<img width="270" height="660" alt="image" src="https://github.com/user-attachments/assets/8f0a7e3b-ae68-4000-bb5e-0fafdb5807fa" />


- 카테고리, 제목, 본문은 필수 입니다.
- 필요할 경우 사진 및 엽서를 추가 할 수 있습니다.
- 작성 중인 둥지를 임시저장하면 다른 곳으로 이동하더라도 저장된 위치에 생성될 둥지 제작을 이어갈 수 있습니다.



### 설정 창

<img width="270" height="660" alt="image" src="https://github.com/user-attachments/assets/89e24ef6-99a8-4b56-bfae-9beede048ef9" />


- 탐색 반경 및 카테고리 필터 사용 여부를 정할 수 있습니다.
- 관리자에게 문의사항을 보낼 수 있습니다.



### 마이페이지

<img width="270" height="660" alt="image" src="https://github.com/user-attachments/assets/7fe2efeb-5dc2-44eb-8a05-8b58eb7df6e1" />


<img width="270" height="660" alt="image" src="https://github.com/user-attachments/assets/0a6e9ebb-19d2-41d5-a93c-ae4d7d0aa89a" />


- 활동을 모아볼 수 있는 페이지입니다. 둥지, 댓글, 엽서 등을 확인할 수 있습니다.
- 프로필 수정이 가능합니다.
- 엽서함에서 엽서 생성이 가능합니다.



### 문의사항 창

<img width="270" height="660" alt="image" src="https://github.com/user-attachments/assets/e6843a89-1ebf-4e75-8c9e-5fff377c974d" />


- 문의사항 답변 및 공지사항 확인이 가능합니다.

## 광고주 페이지



### 광고주 대시보드

<img width="1911" height="946" alt="image" src="https://github.com/user-attachments/assets/331f2721-735b-4e68-b69f-e3aefe1a363c" />


- 계정 상태( 총 허용 광고, 게시 중인 광고, 심사 중인 광고, 추가로 신청 가능한 광고)를 확인할 수 있습니다.
- 신청한 광고의 상태를 확인할 수 있습니다.
- 게시 중인 광고의 성과(노출 수, 클릭 수)를 확인할 수 있습니다.
- ‘새 광고 신청’ 버튼을 눌러 새로운 광고 둥지를 작성 할 수 있습니다.


### 광고 신청 페이지

<img width="1913" height="940" alt="image" src="https://github.com/user-attachments/assets/c8f0a789-3923-4969-a921-c9aefaf998b3" />



- 광고 둥지를 작성하여 신청할 수 있는 페이지 입니다.
- 일반적인 둥지 작성과 거의 동일하게 작성 가능하며, 둥지가 찍힐 위치의 경우 지도 위의 핀을 통해 직접 설정할 수 있습니다.

## 관리자 페이지


### 유저 관리

<img width="2559" height="1344" alt="image" src="https://github.com/user-attachments/assets/9646fde2-be9e-4b51-a25e-bbb4eaf7b2d5" />

- 모든 유저의 정보를 테이블을 통해 확인할 수 있습니다.
- 이메일로 유저 검색이 가능합니다.
- 유저 테이블 행 클릭 시 유저에게 제재를 가할 수 있으며, 제재 중인 유저 행 클릭 시 제재 해제가 가능합니다.
- 역할 버튼 클릭을 통해 광고주 권한 부여가 가능합니다.




### 둥지 관리

<img width="2559" height="1348" alt="image" src="https://github.com/user-attachments/assets/bd2a557f-7a12-4e11-a568-bc8acacb55d0" />

- 모든 둥지 정보를 확인할 수 있습니다.
- 테이블 행 클릭 시 오른쪽에서 둥지 상세내용을 바로 확인할 수 있고, 관리자 권한으로 삭제할 수 있습니다.
- 신고가 들어온 둥지와 댓글을 반려하거나, 삭제 및 제재하는 등 관리합니다.



### 신고된 엽서

<img width="2559" height="1342" alt="image" src="https://github.com/user-attachments/assets/02274019-de2f-4ef1-ba8b-91e8e5c0176f" />


- 신고가 들어온 엽서를 관리합니다.
- 엽서 클릭 시 모달로 확인 가능하며 마찬가지로 반려하거나 삭제 및 제재처리 할 수 있습니다.




### 카테고리 관리

<img width="2559" height="1348" alt="image" src="https://github.com/user-attachments/assets/6b8f8672-2322-4aba-8f5c-25b17d3b4431" />

- 앱에서 표시될 카테고리를 생성, 수정, 삭제할 수 있습니다.
- 드래그 앤 드롭을 통해 앱에서 표시될 카테고리의 순서를 변경할 수 있습니다.




### 공지사항

<img width="2559" height="1347" alt="image" src="https://github.com/user-attachments/assets/5762257f-4f71-4a36-ab9b-e5d64cd27276" />

- 유저에게 알릴 공지를 작성할 수 있습니다.
- 처음 작성한 공지는 임시저장되며, 이후 한번 더 체크하고 발행해야합니다.



### 통계확인

<img width="2559" height="1347" alt="image" src="https://github.com/user-attachments/assets/ffac0534-a5bf-4214-ac2b-e38afc7232a5" />


- 서비스의 전반적인 이용률 통계를 확인할 수 있습니다.



### 문의사항

<img width="2559" height="1345" alt="image" src="https://github.com/user-attachments/assets/a6787bea-0178-4476-97a2-b1d36aeb9769" />


- 유저들의 문의사항을 처리합니다.




### 광고관리

<img width="2559" height="1347" alt="image" src="https://github.com/user-attachments/assets/b45a0f0f-d10f-4ae8-a6c9-1991fa5a7002" />

- 광고주들이 신청한 광고 둥지를 수락하거나, 거절할 수 있습니다.
- 광고 둥지들은 광고 관리 탭에서 모두 확인할 수 있습니다.
- 광고 둥지를 관리자 권한으로 삭제할 수 있습니다.




# 설계 및 구현

## 소프트웨어 아키텍처

<img width="929" height="749" alt="image" src="https://github.com/user-attachments/assets/d0485ff3-e6cb-490b-b633-b411abb1f675" />


**본 프로젝트는 대규모 로컬 커뮤니티 서비스를 안정적으로 서비스하기 위해 Android Native 앱, 인앱 웹뷰(Webview) 및 어드민 웹을 아우르는 프론트엔드 아키텍처와 컨테이너 기반의 분산 백엔드 인프라를 채택하고 있다.**

### 🧱 시스템 컴포넌트별 상세 설계

#### 클라이언트 레이어 (Client Layer)

* **Android Native (Jetpack Compose & MVVM)**
  * `Google Maps SDK`와 `OSM (Open Street Maps)`을 결합한 하이브리드 지도 레이어를 구성하여 일반 도로 정보와 세부 산책로 데이터를 동시에 렌더링한다.
  * 백그라운드 환경에서 하드웨어 센서 및 `Geofencing API`를 구동하여, 유저가 지정된 둥지 반경 내에 진입할 시 실시간 위치 검증 및 이벤트를 발생시킨다.
* **Next.js WebView & Admin Web (Next.js 15 & React 19)**
  * Android 앱 내에 임베디드되는 웹뷰(둥지 상세, 마이페이지, 글쓰기 등)와 독립적인 독립형 관리자/광고주 웹 대시보드를 구축한다.
  * `Android WebView Bridge (JavaScript Interface)`를 구현하여 네이티브 하드웨어 기능(위치 권한, FCM 토큰 추출 등)과 웹 콘텐츠 간의 데이터 연동을 최적화한다.
  * `Zustand`를 활용해 가벼우면서도 직관적인 글로벌 상태 관리를 수행하며, 복잡한 어드민 테이블 및 데이터 시각화 요구사항을 처리한다.

#### 인프라 및 애플리케이션 레이어 (Infrastructure & Application Layer)

* **네트워크 엔트리 포인트 (Nginx)**
  * 외부 클라이언트의 모든 HTTPS 요청을 일차적으로 수용하는 리버스 프록시(Reverse Proxy) 역할을 수행한다.
  * 내부 네트워크의 `Spring Boot` 애플리케이션 서버 전면에서 보안 계층을 형성하고 부하 분산의 기반을 마련한다.
* **비즈니스 코어 (Spring Boot 3.4)**
  * `Spring Security`와 `JWT` 필터를 통해 무상태(Stateless) 유저 인증을 처리하며, 내부적으로 `Google OAuth 2.0` API와 연동하여 자격 증명을 수행한다.
  * `Querydsl`과 공간 연산 라이브러리(`JTS`)를 활용해 (경도, 위도) 표준 순서에 기반한 위치 기반 공간 쿼리(Spatial Query)를 처리한다.
  * 실시간으로 발생하는 알림 이벤트는 비동기 스케줄러 및 `FCM (Firebase Cloud Messaging)` 외부 인프라 레이어를 거쳐 클라이언트에 지연 없이 푸시된다.

#### 데이터 및 스토리지 레이어 (Data & Storage Layer)
* **메인 데이터베이스 (MySQL 8.0)**
  * 서비스의 핵심 엔티티(유저, 둥지, 엽서, 광고, 신고 데이터 등) 간의 유기적인 관계 구조를 영속화한다. Spatial Index를 적용하여 반경 기반 탐색 성능을 최적화한다.
* **인메모리 데이터 스토어 (Redis 7.0)**
  * 리프레시 토큰(Refresh Token) 유효성 검증, 일일 엽서 교환 횟수 제한 등 잦은 I/O와 빠른 응답 속도가 필수적인 휘발성 데이터를 분리 관리하여 메인 DB의 부하를 경감시킨다.
* **미디어 최적화 파이프라인 (AWS S3 & CloudFront)**
  * 사용자가 업로드하는 둥지 이미지 및 엽서 미디어 파일을 `AWS S3`에 안전하게 격리 저장한다.
  * 전면에 `AWS CloudFront (CDN)`를 배치하여 엣지 로케이션 캐싱을 유도함으로써, 미디어 데이터 조회 시 트래픽 레이텐시(Latency)를 최소화하고 성능을 확보한다.

## ERD

<img width="3604" height="2916" alt="image" src="https://github.com/user-attachments/assets/9dc3c1ad-8471-4cf7-a3e5-9c9dac4ffbdb" />

**ERD 자세한 설명은 노션 페이지를 참고.**

[![ERD](https://img.shields.io/badge/Notion-ERD%20보기-black?style=for-the-badge&logo=notion)](https://ballistic-bone-7be.notion.site/ERD-335119ac972c80b19001c40ec6b06776?source=copy_link)



## Repository 구조

### BE

```markdown

src/main/java/com/dodo/dodoserver/
├── 📂 domain             # 핵심 비즈니스 로직
│   ├── 📂 ad             # 광고주, 광고 관리
│   ├── 📂 admin          # 어드민 전용 기능 (통계, 제재, 데이터 관리 등)
│   ├── 📂 auth           # 사용자 인증/인가 (OAuth2, JWT, 토큰 관리)
│   ├── 📂 nest           # 둥지(게시물) 생성, 위치 기반 탐색 및 해금 로직
│   ├── 📂 user           # 사용자 프로필, 계정 및 디바이스 정보(fcm) 관리
│   ├── 📂 inquiry        # 사용자 1:1 문의 처리
│   ├── 📂 category       # 둥지 카테고리 관리
│   ├── 📂 notice         # 공지사항 관리
│   ├── 📂 postcard       # 엽서 crud, 교환
│   ├── 📂 report         # 게시물 및 댓글 신고 처리 시스템
│   └── 📂 mypage         # 마이페이지 관리
├── 📂 global             # 공통 설정 및 보안
│   ├── 📂 config         # DB, Redis, Security, Firebase 등 설정
│   ├── 📂 security       # JWT 필터 및 OAuth2 서비스 구현
│   └── 📂 common         # 공통 응답(ApiResponseDto) 및 유틸리티, 상수
├── 📂 infrastructure     # 외부 인프라 서비스
│   ├── 📂 s3             # AWS S3 파일 업로드
│   └── 📂 fcm            # Firebase 푸시 알림
└── 📂 error              # 예외 처리 및 에러 코드 정의

```

### FE

```markdown
src/
├── 📂 app                        # Next.js App Router 페이지
│   ├── 📂 (webview)              # 웹뷰 전용 페이지 (Android 앱 내 렌더링)
│   │   ├── 📂 nests              # 둥지 목록, 상세, 작성, 수정
│   │   ├── 📂 category           # 관심 카테고리 설정
│   │   └── 📂 mypage             # 마이페이지 (엽서함 등)
│   ├── 📂 admin                  # 어드민 관리자 페이지
│   │   ├── 📂 login              # 로그인 및 OAuth 콜백
│   │   ├── 📂 users              # 유저 관리
│   │   ├── 📂 stats              # 통계 확인
│   │   └── 📂 advertise          # 광고 심사
│   └── 📂 advertiser             # 광고주 전용 대시보드
│       └── 📂 proposals          # 광고 신청 및 수정
│
├── 📂 components                 # 재사용 컴포넌트
│   ├── 📂 webview                # 웹뷰 전용 컴포넌트
│   │   └── 📂 nest-detail        # 둥지 상세 관련 (댓글, 이미지 슬라이더 등)
│   ├── 📂 admin                  # 어드민 전용 컴포넌트
│   │   ├── 📂 layout             # 헤더, 네비게이션, 로그아웃 버튼
│   │   └── 📂 stats              # 통계 카드, 차트
│   ├── 📂 advertiser             # 광고주 전용 컴포넌트
│   │   └── 📂 layout             # 광고주 네비게이션 바
│   └── 📂 ui                     # shadcn/ui 공통 컴포넌트
│
├── 📂 lib                        # 유틸리티 및 설정
│   ├── 📂 store                  # Zustand 전역 상태관리 (nestEditorStore 등)
│   ├── 📂 hooks                  # 커스텀 훅 (useBridge 등)
│   ├── 📂 adminApi               # 어드민 API 함수
│   ├── 📄 api.ts                 # 웹뷰 fetch 기반 API 함수
│   ├── 📄 axios.ts               # axios 인스턴스 및 토큰 인터셉터
│   └── 📄 apiAdvertiser.ts       # 광고주 API 함수
│
├── 📂 types                      # TypeScript 타입 정의
│   ├── 📄 index.ts               # 웹뷰 공통 타입
│   ├── 📄 indexAdmin.ts          # 어드민 타입
│   ├── 📄 indexAdvertiser.ts     # 광고주 타입
│   └── 📄 bridge.d.ts            # AndroidBridge 인터페이스 타입
│
└── 📂 utils                      # 유틸리티 함수
    └── 📄 formatters.ts          # 날짜/좌표 포맷 함수
```

### AN

```markdown
src/main/java/com/example/swcapstone_android
├── 📂 data                  # 데이터 레이어 (데이터 소스 및 통신)
│   ├── 📂 remote            # Retrofit 설정, API 서비스 인터페이스, 토큰 인증 인터셉터
│   ├── 📂 model             # 서버 통신에 사용되는 DTO (Request/Response 모델)
│   ├── 📂 bridge            # 웹뷰(Web)와 앱 네이티브 간의 데이터 연동 인터페이스
│   ├── 📂 etc               # 서버 URL 및 환경 설정 관리
│   └── 📄 TokenManager.kt   # 로컬 토큰 저장 및 관리 (SharedPreferences 등)
│
├── 📂 ui                    # 프레젠테이션 레이어 (UI 및 비즈니스 로직 연결)
│   ├── 📂 theme             # Compose 디자인 시스템 정의 (Color, Theme, Type 등)
│   ├── 📂 [Feature]         # 각 기능별 화면 및 ViewModel 구성 (총 13개 도메인)
│   │   ├── 📂 home, login, splash, mypage, setting
│   │   ├── 📂 alarm, postcard, write, category, unlock
│   │   └── 📂 inquiry, inquiryhistory, userdetail
│   ├── 📄 MainActivity.kt   # 앱의 메인 진입점 및 액티비티
│   ├── 📄 NavGraph.kt       # Jetpack Compose 내비게이션 경로 및 화면 전환 제어
│   └── 📄 Screen.kt         # 내비게이션에서 사용할 스크린 정의 및 경로 관리
│
└── 📂 util                  # 유틸리티 및 백그라운드 서비스
    ├── 📂 geofence          # 위치 기반(Geofencing) 탐색 및 브로드캐스트 리시버 관리
    └── 📂 fcm               # Firebase Cloud Messaging 기반 푸시 알림 서비스
```

## 핵심 기술 스택

### BE

| 분류 | 기술 |
| :--- | :--- |
| **Framework** | Spring Boot 3.4.3 |
| **Auth** | Spring Security, Google OAuth 2.0, JWT |
| **Database** | MySQL 8.0, Redis 7.0 |
| **ORM / Query** | Spring Data JPA, Querydsl |
| **Infrastructure** | AWS (EC2, S3, CloudFront), ngrok |
| **DevOps** | Docker, Docker Compose, GitHub Actions |
| **Documentation** | Swagger (SpringDoc) |
| **Testing** | JUnit 5, JaCoCo (Coverage 70%+) |
| **Messaging** | Firebase Cloud Messaging (FCM) |

### FE

| 분류 | 기술 |
| :--- | :--- |
| **Framework** | Next.js 15, React 19 |
| **Language** | TypeScript |
| **Styling** | Tailwind CSS, shadcn/ui |
| **State Management** | Zustand, TanStack Query |
| **HTTP Client** | Axios, Fetch API |
| **Infrastructure** | Vercel |
| **DevOps** | GitHub Actions |
| **Testing** | Vitest, Testing Library, Storybook, Chromatic |
| **Bridge** | Android WebView Bridge |

### AN

| 분류 | 기술 |
| :--- | :--- |
| **Language** | Kotlin 2.x |
| **UI Framework** | Jetpack Compose (Material 3), Navigation Compose |
| **Architecture** | MVVM, Android Architecture Components (ViewModel, StateFlow) |
| **Local DB / Storage** | DataStore (Preferences) |
| **Network** | Retrofit 2, OkHttp3 (Logging Interceptor), Gson |
| **Location / Mapping** | Google Maps SDK for Android, OSM |
| **WebView / Bridge** | WebInterface (JavaScript Bridge via AndroidView) |
| **Security / Hardware** | Mock Location Check, Native Package Visibility Query (`<queries>`) |
| **DevOps / CI·CD** | GitHub Actions (Automated Test Pipeline) |
| **Testing** | JUnit 4, MockK |
| **Messaging** | Firebase Cloud Messaging (FCM) |

## DevOps, 배포

### BE

**본 프로젝트는 GitHub Actions와 Docker를 활용하여 자동화된 배포 프로세스를 따릅니다.**

1. **CI (Continuous Integration)**
   - `develop` 브랜치에 코드가 `push`되거나 PR이 `merge`되면 트리거됩니다.
   - `./gradlew check`를 통해 테스트 및 커버리지를 검증하며, 실패 시 빌드가 중단됩니다.
2. **CD (Continuous Deployment)**
   - 검증된 코드를 기반으로 Docker 이미지를 빌드합니다.
   - 빌드된 이미지를 **Docker Hub**에 푸시합니다.
   - **EC2** 서버에 접속하여 최신 이미지를 `pull` 받고 `docker-compose up`을 통해 자동화 된 배포를 수행합니다.

보안을 위해 환경 변수는 GitHub Secrets를 통해 런타임에 주입됩니다. 배포를 위해 다음 시크릿 설정이 필요합니다.

| 구분 | 시크릿 키 (Secret Key) | 설명 |
| :--- | :--- | :--- |
| **Infrastructure** | `EC2_HOST`, `EC2_SSH_KEY` | 배포 서버 접속 정보 |
| | `DOCKERHUB_USERNAME`, `DOCKERHUB_TOKEN` | 도커 이미지 푸시 권한 |
| **Application** | `DB_NAME`, `DB_USERNAME`, `DB_PASSWORD` | MySQL 데이터베이스 정보 |
| | `GOOGLE_CLIENT_ID`, `GOOGLE_CLIENT_SECRET` | OAuth2 로그인 연동 |
| | `JWT_SECRET`, `JWT_EXPIRATION_*` | 토큰 발급 및 만료 설정 |
| | `AWS_ACCESS_KEY`, `AWS_SECRET_KEY`, `AWS_REGION` | S3 스토리지 연동 |
| **External** | `FIREBASE_SERVICE_ACCOUNT` | FCM 알림 발송용 서비스 계정 JSON |


### FE

본 프로젝트는 GitHub Actions와 Vercel을 활용하여 자동화된 CI/CD 프로세스를 따릅니다.

1. **CI (Continuous Integration)**
   - `develop` 브랜치에 코드 푸시 및 PR 생성 시, GitHub Actions 워크플로우가 트리거됩니다.
   - **Next.js Production Build** 검증을 수행하여, 개발 환경에서 잡지 못한 오류(정적 최적화 및 서스펜스 지뢰)를 배포 전에 차단합니다.
   - **Vitest**를 통해 유닛 테스트 및 로직 검증을 수행하여 사이드 이펙트를 방지합니다.
   - **시각적 회귀 및 인터랙션 테스트 (`Storybook` & `Chromatic`)**
     - Chromatic 자동화 파이프라인을 연동하여, 컴포넌트 단위의 UI 변경 사항을 추적하는 시각적 회귀 테스트를 수행합니다.
     - PR 단계에서 의도치 않은 디자인 깨짐 등을 사전에 감지하고, 팀원의 시각적 승인(Approve)을 받도록 강제하여 UI 품질을 철저히 관리합니다.

2. **CD (Continuous Deployment)**
   - CI 검증을 통과한 코드는 Vercel을 통해 프로덕션 환경으로 자동 배포됩니다.
   - 모든 PR마다 독립적인 Preview 배포 링크가 생성되어, 기능 단위의 화면 검증 및 피드백 루프를 구축했습니다.
	
환경 변수는 GitHub Secrets와 Vercel을 통해 주입됩니다. 시각적 회귀 테스트 및 배포를 위해 다음 설정이 필요합니다.

**GitHub Secrets**

| 구분 | 시크릿 키 (Secret Key) | 설명 |
| :--- | :--- | :--- |
| **Storybook** | `CHROMATIC_PROJECT_TOKEN` | Chromatic 시각적 회귀 테스트 토큰 |

**Vercel Environment Variables**

| 구분 | 변수명 | 설명 |
| :--- | :--- | :--- |
| **Application** | `NEXT_PUBLIC_SERVER_URL` | 백엔드 API 서버 주소 |
| | `NEXT_PUBLIC_SERVER_IP` | 백엔드 API 서버 주소 (동일) |
| | `NEXT_PUBLIC_KAKAO_MAP_KEY` | 카카오 지도 API 키 |

### AN

CI/CD 파이프라인

본 프로젝트는 GitHub Actions를 활용하여 코드 검증부터 테스트, 그리고 Firebase를 통한 내부 테스터 자동 배포까지 일련의 파이프라인을 자동화했습니다.

---

CI (Continuous Integration)

> `develop` 브랜치에 코드가 **push**되거나 **Pull Request**가 merge되면 자동 트리거됩니다.

Android Instrumented Test (UI/통합 테스트)

1. GitHub Actions 러너 내에서 가상 환경인 **ReactiveCircus Android Emulator Runner**를 구동합니다.
2. **하드웨어 가속(KVM)** 기반의 에뮬레이터를 가동하여 실제 기기와 동일한 환경을 구성합니다.
3. 구글맵 레이어 및 UI 상호작용 검증을 수행합니다.

./gradlew connectedDebugAndroidTest

> ⚠️ 테스트 실패 시 파이프라인이 **즉시 중단**됩니다.

---

CD (Continuous Deployment)

CI 단계의 모든 검증(유닛 테스트 및 에뮬레이터 통합 테스트)을 통과한 무결한 코드를 기반으로 배포 프로세스를 시작합니다.

**1. APK 빌드**

배포용 빌드 명령을 수행하여 안드로이드 실행 파일(APK/AAB)을 생성합니다.

```bash
./gradlew assembleDebug   # 디버그 APK 빌드
# 또는
./gradlew bundleRelease   # 릴리즈 AAB 빌드
```

**2. Firebase App Distribution 자동 배포**

| 단계 | 내용 |
|------|------|
| 업로드 | 빌드된 APK를 Firebase App Distribution 인프라로 자동 업로드 |
| 인증 | GitHub Actions에 등록된 Firebase Credentials(Token)로 안전하게 처리 |
| 알림 | 등록된 내부 개발자 및 QA 테스터에게 새 버전 출시 이메일 자동 발송 |
| 테스트 | 테스터는 기기에서 즉시 다운로드하여 최신 기능 검증 가능 |

## 테스트 정책

### BE

**📊 테스트 커버리지 정책 (Test Coverage Policy)**

코드 품질 관리 및 안정성 확보를 위해 **JaCoCo**를 통한 테스트 커버리지를 강제하고 있습니다.

1. 커버리지 기준 (Quality Gate)
- **전체 커버리지 하한선: 70%** (70% 미달 시 빌드 실패)
- **주요 측정 지표**:
    - **LINE**: 소스 코드 라인 기준 실행 비율
    - **INSTRUCTION**: 자바 바이트코드 명령 단위 실행 비율 (가장 정밀한 지표)
    - **BRANCH**: 조건문(`if`, `switch` 등)의 분기 실행 비율 (최소 50% 이상 권장)

2. 리포트 확인 방법
빌드 완료 후 로컬 환경에서 상세한 커버리지 리포트를 확인할 수 있습니다.
- **경로**: `build/reports/jacoco/test/html/index.html`
- 해당 파일을 브라우저로 열면 클래스별, 메서드별 상세 커버리지 현황(실행된 라인/미실행된 라인)을 시각적으로 확인할 수 있습니다.

3. 측정 제외 대상 (Exclusions)
순수 비즈니스 로직 검증에 집중하기 위해 다음 대상은 측정에서 제외됩니다.
- **QueryDSL 생성 클래스**: `**/Q*`
- **데이터 객체**: `**/*Dto*`, `**/*Request*`, `**/*Response*`
- **예외 처리 및 에러 코드**: `**/*Exception*`, `**/*ErrorCode*`
- **설정 및 보안**: `global/config/**`, `global/security/**`

### FE

**🧪 Frontend Testing Policy (프론트엔드 테스트 정책)**

🎯 테스트 핵심 원칙 (Testing Principles)
- **역할의 철저한 분리**: 화면(UI 스타일) 검증과 기능(비즈니스 로직) 검증을 분리하여 테스트 코드 유지보수 비용을 최소화합니다.
- **자동화 검증 필수**: 작성된 모든 테스트는 로컬 환경에만 머무르지 않고, **GitHub Actions(CI)** 파이프라인과 연동되어 성공 지표를 달성해야만 브랜치 머지(Merge)가 가능합니다.

🧱 레이어별 검증 범위 및 담당 도구

| 테스트 종류 | 담당 도구 | 테스트 대상 및 범위 (What to test) | 품질 관리 기준 |
| :--- | :--- | :--- | :--- |
| **단위 테스트**<br>(Unit Test) | **Vitest** | • UI와 연결되지 않은 **순수 비즈니스 로직**<br>• 어드민 API 데이터 가공 및 정렬/필터링 함수<br>• 공통 유틸리티 함수 (토큰 파싱, 날짜 포맷팅 등) | 핵심 실패 케이스<br>(Edge Case)<br>**통과율 100%** |
| **인터랙션 테스트**<br>(Component Test) | **Storybook**<br>*(Play 함수)* | • 컴포넌트 단위의 **사용자 행동 시나리오 검증**<br>• 어드민 주요 기능 (둥지 관리 페이지네이션, 공지사항 체크박스 다중 선택 및 테이블 렌더링 등) | 핵심 유저 시나리오<br>**성공률 100%** |
| **시각적 회귀 테스트**<br>(Visual Test) | **Chromatic** | • 브라우저 픽셀 레벨에서의 **디자인/스타일 깨짐 검증**<br>• 페이지 수정 시 발생 가능한 CSS 사이드 이펙트 차단 | 매 PR 빌드 시<br>**팀원 전원 승인<br> 필수** |


🛑 Do & Don't

❌ 이것은 테스트하지 않습니다 (Don't)
- **외부 라이브러리 자체 기능**: `Shadcn UI`나 `Radix UI` 등 검증된 라이브러리 자체의 내장 스타일 및 동작은 신뢰하고 테스트 대상에서 제외합니다.
- **순수 정적 컴포넌트**: 단순 마크업만 존재하는 UI(고정 아이콘, 단순 텍스트 레이블 등)는 단위 테스트를 생략하고 스토리북 등록으로 대체합니다.

⭕ 이것은 반드시 테스트합니다 (Do)
- **권한 및 보안 분기**: 유저 등급/권한에 따른 메뉴 노출 및 접근 제어 로직은 `Vitest`로 철저하게 검증합니다.
- **복잡한 상태 구조**: 테이블 페이징, 다중 조건 필터링 등 상태(State)가 복잡하게 얽혀 문제가 발생하기 쉬운 UI 코어는 `Storybook Interaction`으로 테스트 시나리오를 작성해 방어합니다.
- **Next.js Production Build 검증**: 로컬 개발 환경(`npm run dev`)에서는 누락되기 쉬운 타입 체크, 린트 및 빌드 오류를 배포 전 단계에서 완벽하게 솎아냅니다.

# 빌드 방법 (Build Instructions)

## BE

🔨 빌드 방법 (Build Instructions)

프로젝트 빌드 시 JaCoCo 테스트 커버리지 검증이 자동으로 수행됩니다.

**1. 로컬 빌드 및 테스트**
```bash
# 테스트 수행 및 커버리지 확인 (70% 하한선 검사 포함)
./gradlew check

# 빌드 및 JAR 생성
./gradlew build
```

**2. 도커 빌드 및 배포 (Docker Build & Deploy)**
```bash
# 프로젝트를 도커 이미지로 빌드하고 배포하는 스크립트입니다.
#!/bin/bash
set -e

# 1. 테스트 및 검증
./gradlew check --no-daemon

# 2. 도커 이미지 빌드
docker build -t <DOCKERHUB_USERNAME>/dodo-server:latest .

# 3. 도커 허브 푸시
docker push <DOCKERHUB_USERNAME>/dodo-server:latest

# 4. 컨테이너 실행
docker-compose up -d
```

## FE

**1. 의존성 라이브러리 설치** 
`npm install`

**2. 환경 설정 파일 준비 (`.env.local`)**

보안 및 API Key 유출 방지를 위해 `.gitignore` 처리된 환경 변수 파일을 프로젝트 루트 디렉토리에 직접 생성해야 합니다.

**파일 위치:** 프로젝트 최상위 루트 폴더

아래와 같이 백엔드 서버 주소 및 카카오 지도 API 키를 기입합니다.

```properties
NEXT_PUBLIC_SERVER_URL=백엔드 API 실서버 주소
NEXT_PUBLIC_SERVER_IP=백엔드 API 실서버 주소(위와 동일)
NEXT_PUBLIC_KAKAO_MAP_KEY=카카오 개발자 콘솔에서 발급받은 JavaScript 키
```

> ⚠️ **카카오맵 API 사용 전 필수 설정**
>
> 카카오 개발자 콘솔에서 JavaScript 키 발급 후 반드시 아래 설정을 확인하세요.
> 1. [카카오 개발자 콘솔](https://developers.kakao.com) → 내 애플리케이션 → 해당 앱 선택
> 2. **앱 설정 → 카카오맵 → 상태를 ON으로 변경**
> 3. **플랫폼 → Web → 사이트 도메인에 `http://localhost:3000` 추가**
>
> 위 설정을 누락하면 403 Forbidden 또는 카카오맵 API 호출 에러가 발생합니다.

3. 로컬 개발 서버 실행 (Default: http://localhost:3000)
npm run dev

4. 테스트 및 스토리북 실행 (선택)
npm run test:run      # Vitest 실행
npm run storybook     # Storybook 로컬 실행

## AN

*프로젝트 시작 가이드*

**1. 사전 필수 환경 (Prerequisites)**

| 항목 | 버전 |
|------|------|
| IDE | Android Studio Ladybug (또는 최신 정식 버전) |
| JDK | Java Development Kit (JDK) 17 이상 |
| Gradle | 9.4.1 |

---

**2. 환경 설정 파일 준비 (`local.properties`)**

보안 및 API Key 유출 방지를 위해 `.gitignore` 처리된 환경 변수 파일을 프로젝트 루트 디렉토리에 직접 생성해야 합니다.

**파일 위치:** 프로젝트 최상위 루트 폴더

아래와 같이 백엔드 서버 주소 및 Google Maps API 키를 기입합니다.

```properties
sdk.dir=/Users/유저이름/Library/Android/sdk   # 각 운영체제별 SDK 경로
BASE_URL="백엔드 API 실서버 주소"
WEB_URL="웹뷰 연동 주소"
MAPS_API_KEY="AIzaSyA..."                      # Google Cloud Console에서 발급받은 Maps SDK Key
```

---

**3. Google Services 설정 파일 배치**

Firebase Cloud Messaging(FCM) 푸시 알림 연동을 위해 발급받은 `google-services.json` 파일을 아래 경로에 정확히 배치합니다.

```
[Project_Root]/app/google-services.json
```

---

**4. CLI 빌드 및 테스트 (Terminal)**

터미널 환경에서 프로젝트 빌드 및 무결성 검증을 수행하는 명령어 세트입니다.

프로젝트 청소 및 빌드 권한 부여 (최초 1회)

```bash
chmod +x gradlew
./gradlew clean
```

Debug APK 빌드

```bash
./gradlew assembleDebug
```

> 빌드 완료 시 `app/build/outputs/apk/debug/app-debug.apk` 경로에 파일이 생성됩니다.

---

5. Android Studio를 통한 기기 실행 (Run)

1. Android Studio를 실행한 뒤 **Open** 버튼을 눌러 프로젝트 폴더를 선택합니다.
2. **Gradle Sync**가 완료될 때까지 대기합니다.
3. 아래 중 하나의 방법으로 타겟 기기를 준비합니다.
   - **실기기:** 안드로이드 스마트폰을 USB로 연결 (개발자 옵션 및 USB 디버깅 활성화 필수)
   - **에뮬레이터:** AVD(Android Virtual Device) 가동
4. 상단 툴바의 **Run ▶** (초록색 재생 버튼)을 클릭하면 앱이 컴파일되어 타겟 기기에 자동으로 설치 및 실행됩니다.

# 협업 규칙 (Collaboration Rules)

## 공통

이 프로젝트는 원활한 협업과 코드 품질 관리를 위해 다음 규칙을 따릅니다.

**1. 브랜치 전략 (Branch Strategy)**
브랜치명은 `kebab-case`를 사용합니다.
- **형식**: `type/issue-number/description`
- **예시**: `feat/12/login-api`, `fix/45/security-patch`

**2. 커밋 컨벤션 (Commit Convention)**
커밋 메시지에는 반드시 관련 이슈 번호를 포함합니다.
- **형식**: `type/#issue-number: subject`
- **예시**: `feat/#12: 로그인 API 구현`, `fix/#45: 토큰 만료 로직 수정`

| 커밋 유형 | 의미 |
| --- | --- |
| `feat` | 새로운 기능 추가 |
| `fix` | 버그 수정 |
| `docs` | 문서 수정 |
| `refactor` | 코드 리팩토링 |
| `test` | 테스트 코드, 리팩토링 테스트 코드 추가 |
| `chore` | 패키지 매니저 수정, 그 외 기타 수정 ex) .gitignore |
| `!HOTFIX` | 급하게 치명적인 버그를 고쳐야 하는 경우 |

## BE

### 백엔드 협업 및 코드 개발 규칙 가이드

**1. 개발 및 코드 규칙 (Coding Standards)**

  지속 가능한 코드 품질과 공간 데이터의 정확성을 위해 다음 제약 사항을 엄격히 준수합니다.

  - 공간 데이터 표준 (Spatial Data)
   - 모든 공간 데이터(GPS) 처리는 (Longitude, Latitude / 경도, 위도) 순서를 표준으로 사용합니다.
   - 데이터베이스(MySQL) 저장 및 애플리케이션(Java/JTS) 연산 시 이 순서가 뒤바뀌지 않도록 상시 점검합니다.

  - 에러 처리 및 응답 (Response)
   - 모든 API 응답은 ApiResponseDto 규격을 사용하며, 성공/실패 여부와 관계없이 일관된 필드(status, code, message, data)를 반환합니다.
   - 임의의 에러 메시지 대신 ErrorCode Enum에 정의된 코드를 사용하여 프론트엔드와의 통신 규약을 유지합니다.

**2. 테스트 및 품질 관리 (Testing & QA)**

  품질이 검증되지 않은 코드는 배포할 수 없습니다.

  - 단위 및 회귀 테스트
   - 새로운 기능 추가 시 해당 로직을 검증하는 테스트 코드를 반드시 포함해야 합니다.
   - 버그 수정 시, 해당 버그가 재발하지 않음을 증명하는 회귀 테스트를 먼저 작성하여 실패를 확인한 후 수정을 진행합니다.

  - 품질 지표 및 CI 연동
   - JaCoCo 커버리지: 핵심 로직이 포함된 Service 및 Controller 레이어의 라인 커버리지를 70% 이상으로 유지합니다. 커버리지 미달 시 빌드가
     실패하도록 설정되어 있습니다.
   - CI 연동: 모든 Pull Request(PR)는 GitHub Actions를 통한 ./gradlew check를 반드시 통과해야 머지 및 배포가 가능합니다.

**3. 문서화 및 보안 (Docs & Security)**

  정보 유출 방지와 지식 공유를 위한 규칙입니다.

  - 보안 및 환경 설정
   - 어떠한 경우에도 소스 코드나 로그에 비밀번호, API 키, 시크릿 키 등을 하드코딩하지 않습니다.
   - 모든 민감 정보는 application.yml의 환경 변수 처리 또는 GitHub Secrets를 통해 주입하며, .env 파일은 커밋 대상에서 제외합니다.

**4. 에러 핸들링 가이드 (Error Handling)**

  일관된 예외 처리를 위해 BusinessException 중심의 흐름을 따릅니다.

  - 에러 응답 규격
   - 에러 발생 시 다음과 같은 JSON 형식을 유지합니다.
   - { "status": "ERROR", "code": "U001", "message": "사용자를 찾을 수 없습니다.", "data": null }

  - 예외 처리 흐름
   - 1. ErrorCode 정의: com.dodo.dodoserver.error.ErrorCode에 도메인별 접두사(User: U, Nest: N 등)를 사용하여 코드를 정의합니다.
   - 2. 비즈니스 예외 발생: 로직 검증 실패 시 new BusinessException(ErrorCode.NAME)을 던집니다.
   - 3. 전역 처리: GlobalExceptionHandler가 이를 캐치하여 설정된 HTTP 상태 코드와 메시지로 자동 응답합니다.

**5. 기타 준수 사항**

  - 커밋 및 작업 단위
   - 기능 구현(feat)과 해당 기능을 검증하는 테스트 코드(test)는 서로 다른 커밋으로 분리하여 기록합니다.
   - 하나의 커밋에는 하나의 논리적 변경 사항만 담아 리뷰 효율을 높입니다.

  - 기술적 권장 사항
   - 공간 연산 쿼리 작성 시 성능 최적화를 위해 Querydsl과 네이티브 쿼리를 적절히 혼용하며, 카테시안 곱 발생 여부를 반드시 확인합니다.
   - 복잡한 비즈니스 로직은 서비스 레이어에서 처리하고, 엔티티는 가급적 순수한 상태를 유지하거나 도메인 로직만 포함합니다.

### 패키지 구조 및 도메인 개발 규칙

**1. 도메인 중심의 패키지 구성 (Domain-Driven Packaging)**

  비즈니스 로직의 응집도를 높이기 위해 도메인을 최상위 단위로 구성합니다.

  - 도메인별 내부 계층화
   - domain/{domain_name} 하위에 controller, service, entity, dao, dto 패키지를 엄격히 분리합니다.
   - 새로운 기능을 추가할 때는 기존 도메인에 포함될 수 있는지 먼저 확인하며, 없을 경우 새로운 도메인 패키지를 생성합니다.

  - Repository 명칭 및 위치 (DAO)
   - 우리 프로젝트는 Spring Data JPA의 Repository를 dao 패키지 내에 위치시킵니다.

**2. 관리자 도메인 분리 (Admin Domain Separation)**

  관리자 전용 기능은 일반 사용자 로직과 섞이지 않도록 격리합니다.

  - 관리자 패키지 구조
   - domain/admin/{target_domain} 구조를 유지합니다 (예: admin/user, admin/nest).
   - 관리자 전용 비즈니스 로직과 데이터 접근 로직은 일반 사용자용 Service/DAO를 재사용하기보다 별도의 AdminService, AdminDAO를 구축하여 의존성
     엉킴을 방지합니다.

**3. 글로벌 및 인프라 레이어 관리 (Global & Infrastructure)**

  공통 관심사와 외부 연동 로직은 별도의 전용 패키지에서 관리합니다.

  - Global 패키지 역할
   - global/config: Security, Redis, S3, Querydsl 등 프로젝트 전반의 설정 파일을 관리합니다.
   - global/common: 모든 도메인에서 공통으로 사용하는 ApiResponseDto, 유틸리티 클래스, 상수를 위치시킵니다.
   - global/security: JWT 제공자, 인증 필터, OAuth2 성공 핸들러 등 보안 관련 핵심 로직을 관리합니다.

  - Infrastructure 패키지 역할
   - infrastructure/fcm, infrastructure/s3와 같이 외부 시스템과의 물리적 통신을 담당하는 구현체는 infrastructure 패키지에서 관리합니다.
   - 도메인 서비스는 이 인프라 서비스를 주입받아 사용함으로써 기술적 세부 사항으로부터 비즈니스 로직을 보호합니다.

**4. DTO 및 엔티티 활용 규칙 (DTO & Entity Usage)**

  데이터 이동과 데이터베이스 매핑의 역할을 명확히 분리합니다.

  - DTO 사용 원칙
   - controller와 service 사이의 데이터 전달은 반드시 dto 패키지에 정의된 객체를 사용합니다.
   - 외부 API 노출 시 엔티티를 직접 반환하는 것을 금지하며, 요청(RequestDto)과 응답(ResponseDto) 객체를 명확히 분리하여 정의합니다.

  - 엔티티 관리
   - 모든 도메인 엔티티는 domain/{domain_name}/entity 패키지에 위치합니다.
   - 엔티티 내부에서 Soft Delete 필터 등 도메인 특화된 설정을 관리하며, @Setter 사용을 지양하고 의미 있는 비즈니스 메서드를 통해 상태를
     변경합니다.

**5. 예외 및 에러 코드 위치 (Error Handling)**

  일관된 예외 처리를 위해 지정된 패키지만 사용합니다.

  - Error 패키지 구조
   - error/ErrorCode: 프로젝트 전체에서 사용하는 에러 코드를 관리합니다.
   - error/exception: BusinessException과 같은 커스텀 예외를 관리합니다.
   - error/GlobalExceptionHandler: 모든 예외를 낚아채서 ApiResponseDto 형식으로 변환하는 컨트롤러 어드바이스를 관리합니다.

**6. 테스트 코드 패키지 미러링 (Test Mirroring)**

  - 테스트 코드의 가독성과 접근성을 위해 메인 코드와 동일한 구조를 유지합니다.


## FE

### 개발 및 코드 규칙 (Coding Standards)

지속 가능한 코드 품질을 위해 다음의 제약 사항을 준수합니다.

- **타입 안전성**: `any` 타입 사용을 지양하고 명확한 TypeScript 타입을 정의합니다.
- **컴포넌트 설계**: 외부 의존성(API, 브릿지) 없는 컴포넌트를 우선 분리하여 재사용성을 높입니다.
- **에러 처리**: fetch 기반 API는 `res.ok` 체크, axios 기반 API는 interceptor를 통해 일관된 에러 처리를 수행합니다.


### 테스트 및 품질 관리 (Testing & QA)

- **단위 테스트 필수**: 새로운 순수 비즈니스 로직 추가 시 Vitest 테스트 코드를 포함해야 합니다.
- **시각적 회귀 테스트**: UI 컴포넌트 변경 시 Storybook 스토리를 작성하고 Chromatic을 통해 검증합니다.
- **회귀 테스트**: 버그 수정 시 해당 버그가 재발하지 않음을 증명하는 테스트를 먼저 작성합니다.
- **CI 연동**: 모든 PR은 GitHub Actions의 타입 체크, 린트, 빌드, 테스트를 통과해야 머지가 가능합니다.

### 문서화 및 보안 (Docs & Security)

- **비밀 키 관리**: 어떠한 경우에도 소스 코드에 API 키나 시크릿을 하드코딩하지 않습니다. 모든 환경 변수는 `.env.local`과 GitHub Secrets를 통해 관리합니다.
- **브랜치 보호**: `main`, `develop` 브랜치는 직접 push를 금지하며 반드시 PR을 통해 머지합니다.

## AN

### 개발 및 코드 규칙 (Coding Standards)

지속 가능한 코드 품질을 위해 다음의 제약 사항을 준수합니다.

- **타입 안전성**: `Any` 타입 사용을 지양하고 명확한 Kotlin 타입 및 `data class`를 정의합니다.
- **컴포넌트 설계**: 외부 의존성(API, Bridge) 없는 Composable을 우선 분리하여 재사용성과 Preview 가능성을 높입니다.
- **에러 처리**: Retrofit 기반 API는 `Response<T>` 래핑 및 OkHttp Interceptor를 통해 일관된 에러 처리를 수행합니다.
- **ViewModel 규칙**: UI 상태는 `StateFlow`로 단방향 관리하며, ViewModel에서 직접 View를 참조하지 않습니다.


### 테스트 및 품질 관리 (Testing & QA)

- **단위 테스트**: 새로운 순수 비즈니스 로직(UseCase, ViewModel) 추가 시 JUnit 4 및 MockK 테스트 코드를 포함해야 합니다.
- **UI 테스트**: 주요 화면 변경 시 Compose UI Test(`composeTestRule`)를 통해 핵심 상호작용을 검증합니다.
- **CI 연동**: 모든 PR은 GitHub Actions의 빌드 및 `connectedDebugAndroidTest`를 통과해야 머지가 가능합니다.


### 문서화 및 보안 (Docs & Security)

- **비밀 키 관리**: 어떠한 경우에도 소스 코드에 API 키나 시크릿을 하드코딩하지 않습니다. 모든 환경 변수는 `local.properties`와 GitHub Secrets를 통해 관리합니다.
- **Mock Location 차단**: 위치 기반 기능의 무결성을 위해 Mock Location 탐지 로직을 유지하며 임의로 비활성화하지 않습니다.
- **브랜치 보호**: `main`, `develop` 브랜치는 직접 push를 금지하며 반드시 PR을 통해 머지합니다.
