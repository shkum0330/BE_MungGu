# 🐾 강아지 동반 시설 공유 플랫폼, 멍티비티
![프로젝트 화면 (2)](https://github.com/user-attachments/assets/3693024a-bc43-4b44-acb9-a7f68e7114ea)
<br/>


<br><br>

## 📋 프로젝트 소개
LG U+ 유레카 1기 최종 융합 프로젝트 우수상 수상 <br/><br/>
멍티비티(반려경 동반 가능 시설 플랫폼) <br/>
<br/>
현대 사회에서 반려동물은 가족의 일원으로 자리 잡고 있습니다. 이에 따라 반려견과 함께할 수 있는 공간에 대한 수요가 증가하고 있으며, 반려견과 함께 이동할 수 있는 시설에 대한 정보 또한 중요해졌습니다. 본 프로젝트는 반려견 동반 가능 시설을 찾고자 하는 반려인과 이러한 시설을 제공하는 사업자를 연결하는 플랫폼을 개발하는 것을 목표로 합니다.
<br/>

배포 주소 : <b>https://mungtivity.vercel.app/ </b> <br/>
프로젝트 기간 : 2024.11.12 ~ 2024.12.19

<br>

## 👨🏻‍💻 팀원

| <img src="https://github.com/user-attachments/assets/209ee765-9f67-40bb-a5fc-44a588733c8c" width="100px;" alt=""/> | <img src="https://github.com/user-attachments/assets/d045766b-332a-4cd2-ae44-213ab1442187" width="100px;" alt=""/> | <img src="https://github.com/user-attachments/assets/c5d2312e-8c9a-442e-ae41-1f8fc8541db9" width="100px;" alt=""/> | <img src="https://github.com/user-attachments/assets/71b3624e-d71a-48d2-9dda-53bc94cb4a9a" width="100px;" alt=""/> | <img src="https://github.com/user-attachments/assets/01189ba3-399d-48e0-83c9-691c1404b3d5" width="100px;" alt=""/> | <img src="https://github.com/user-attachments/assets/d85c19eb-1072-48f5-b127-42cd9dfc662d" width="100px;" alt=""/> | <img src="https://github.com/user-attachments/assets/a252f1bf-36b4-4222-b6d3-c151f586d1c3" width="100px;" alt=""/> | <img src="https://github.com/user-attachments/assets/84dcdda9-9d55-413f-853e-caf1ea384d37" width="100px;" alt=""/>
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [고창준](https://github.com/ckdwns1221) | [금세현](https://github.com/shkum0330) | [김병옥](https://github.com/OkKim99) | [김영동](https://github.com/youngdongkim1) | [이신지](https://github.com/kuma0112) | [이은석](https://github.com/EunSeok-222) | [장현희](https://github.com/hh830) | [채희원](https://github.com/heeeione) | 
| <b> FE </b> | <b> BE </b> | <b> BE </b> | <b> FE </b> | <b> BE </b> | <b> FE </b> | <b> BE </b> | <b> FE </b> |

### R&R
| 파트 | 이름 | 역할 |
| ------------ | -------------------------------------------------------------- | ----------------------------------------------------- |
| **FE** | 고창준 | 피그마 디자인, 소셜 로그인, 회원정보 등록, 관심사 설정, 멍생네컷 담당 |
| **BE** | 금세현 | 즐겨찾기, 후기, 금칙어 필터링 |
| **BE** | 김병옥 | 반려동물 CRUD, 견종 검색, 실시간 인기장소 조회, 장소 상세 조회 |
| **FE** | 김영동 | 메인페이지, 추천 장소 조회, 핫한 장소 조회, 검색 기능 |
| **BE** | 이신지 | 소셜 로그인, 회원 등록 및 관리, 장소/펜션 검색, 멍생네컷 |
| **FE** | 이은석 | 반려동물 CRUD, 견종 검색, 실시간 인기장소 조회, 장소 상세 조회, 최근 본 목록 조회 |
| **BE** | 장현희 | 추천 시스템, 크롤링, 날씨 API, 지도 기능, 최근 후기 조회 |
| **FE** | 채희원 | 지도 API, 즐겨찾기, 장소 검색, 최근 검색 기록, 길찾기 |
<br>


## 🔎 서비스 개발 동기 및 목적
반려동물을 양육하고 있는 가구는 23년 기준 28.2%로 점점 증가하는 추세이고, 그 중에서도 강아지를 키우는 비율이 높은 것을 확인할 수 있었습니다
하지만 반려동물 출입 가능 장소는 제한되어 있고, 이에 대한 정보를 기존 지도에서 쉽게 찾기가 어려웠습니다.
따라서 저희 서비스는 사용자가 '반려동물 동반 가능 시설을 손쉽게 조회하는 것'과 '반려동물과의 추억 기록'을 목표로 서비스를 개발하였습니다.
<br>



## 🎯 문제 정의와 솔루션
### 문제 정의
**1. 정보 부족**
- 반려동물과 함께할 수 있는 시설 정보가 제한적이며, 여러 플랫폼에 흩어져 있어 원하는 정보를 쉽게 찾기 어렵습니다.

**2. 검색의 불편함**
- 반려동물 동반 가능 시설이라도 강아지의 종이나 체중에 따라 입장 가능 여부가 달라지지만, 기존 플랫폼에서는 이를 세부적으로 검색하기 어렵습니다.

### 솔루션
**1. 사용자 편의성 개선**
- 반려동물 동반 가능 시설 공유 플랫폼을 통해 동반 가능한 장소를 한눈에 확인할 수 있으며, 사용자의 반려동물 특성에 맞는 맞춤형 시설을 추천받을 수 있습니다.

**2. 구체적인 검색 필터 제공**
- 지역과 장소명 검색은 물론, 반려동물의 종이나 체중에 따른 입장 가능 여부까지 세부적으로 검색할 수 있습니다.
- 검색 시 지역별 날씨 정보도 함께 제공하여 사용자가 더욱 편리하게 검색할 수 있도록 지원합니다.
<br/>


## 👩‍💻 서비스 소개
### 개요
### 주요 기능
**1. 소셜 로그인**
- 카카오 소셜 로그인<br>
  <img src="https://github.com/user-attachments/assets/d2252adf-1129-466d-a8fc-43e70b03be4e" width="300">
<br>

**2. 마이페이지**
  - 회원 정보 CRUD, 내 반려견 목록 조회 및 등록 가능
    
  - 선호 시설과 선호 지역 정보 수정 가능 <br>
  <img src="https://github.com/user-attachments/assets/46c795a6-c8c0-4be6-8080-e4e37ba86ed4" width="200">
  <img src="https://github.com/user-attachments/assets/e32e0996-7e0d-4473-9048-1e39aac1237d" width="200"> 
  <img src="https://github.com/user-attachments/assets/ad1e2fcf-f465-4a9d-8ed6-63fadd5d2c99" width="200">
  <img src="https://github.com/user-attachments/assets/8c896de3-4b03-49bd-9208-0d015aa4df11" width="200">
<br>

**3. 반려동물 정보 관리**
- 반려동물 프로필 관리 (CRUD) <br>
  <img src="https://github.com/user-attachments/assets/58c1bae1-030b-4914-8f18-671dc7c3ce1e" width="300">
  <img src="https://github.com/user-attachments/assets/9b99baec-89a1-4fbf-8aa6-c0ba26ed1210" width="300">
<br>

**4. 검색**
- 검색어로 검색
  
- 지역, 날짜, 같이 갈 반려동물 선택 후 해당 정보를 반영하여 장소 검색
  
- JooQ를 도입하여 로그인 여부에 따른 좋아요 검색, 페이징 여부에 따른 검색 등 동적으로 검색 가능
  
- 기상청 단기 예보 조회 API와 중기 예보 조회 API를 사용하여 지역 선택 시 당일부터 10일 후까지의 날씨 정보 제공 <br>
  <img src="https://github.com/user-attachments/assets/06945f78-48b1-40f8-9024-412028dee7ab" width="230">
  <img src="https://github.com/user-attachments/assets/f8e289f6-0793-4dd2-8466-5ab83a498f84" width="230">
  <img src="https://github.com/user-attachments/assets/0cc44480-665e-4ed5-91e2-06fe785f7e5c" width="230">

<br>

**5. 즐겨찾기**
- 장소에 즐겨찾기를 할 수 있고, 즐겨찾기 한 장소를 모아 볼 수 있다. 
  <br>
  
  <img src="https://github.com/user-attachments/assets/973be577-cf63-47d2-aa46-62c282e25814" width="300">
  <img src="https://github.com/user-attachments/assets/47207dc8-cb6a-49f5-947a-5bf43a68c5cc" width="300">

<br>

**6. 후기**
- 장소에 사진, 영상을 포함한 후기를 남길 수 있고, 내가 쓴 후기를 모아 볼 수 있다.
  <br>
  
  <img src="https://github.com/user-attachments/assets/0fbcbd6f-c071-43fc-9153-798fae13bdb7" width="500">
  <img src="https://github.com/user-attachments/assets/98ad9968-101d-45ea-b40c-a23eadaebe6f" width="500">

<br>

**7. 지도**
- 즐겨찾기 한 장소의 정보를 알 수 있다.
  
- 즐겨찾기 한 장소의 위치를 핀을 통해 알 수 있다.
  
- 지도에서 장소를 검색할 수 있다.
  <br>
  <img src="https://github.com/user-attachments/assets/2c164a0c-5740-40f6-8b2f-47e6f25ab148" width="400">
  <img src="https://github.com/user-attachments/assets/6af37592-f6e0-4c49-9f95-08f12b7c1e19" width="400">

<br>

**8. 길찾기**
- 현재 위치에서 특정 장소까지 가는 길을 조회할 수 있다.
   <br>
    <img src="https://github.com/user-attachments/assets/372ca62c-91ea-4004-b770-450c6dc04c72" width="400">

<br>

**9. 추천**
- 개인 별 펜션 추천과 펜션 연관 시설 추천
  
- 콘텐츠 기반 필터링과 협업 필터링을 사용하여 보다 정확한 추천
  
- 협업 필터링에서 대규모 데이터 처리와 기계 학습 기반 추천 라이브러리 Mahout을 사용
  
- 사용자의 리뷰 데이터와 선호 지역을 기반으로 개인 별 맞춤 펜션 추천 제공  
- 사용자의 리뷰 데이터와 거리를 기반으로 펜션 연관 시설 추천 제공<br>

  <img src="https://github.com/user-attachments/assets/0dbf1aea-7945-46ee-8f21-0a4198875aec" width="500">
  <img src="https://github.com/user-attachments/assets/84fc8f52-8342-4dae-aae3-16bffba65c35" width="500">

<br>

**10. 조회 수 기반 핫한 장소**
- 조회 수를 기반으로 핫한 장소를 카테고리 별로 조회 가능
- Redis의 Sorted Set 자료구조 사용 (Score 기준으로 조회수 자동 정렬에 용이할 것이라 판단)
- 로그성 테이블과 비즈니스 테이블 분리
  <br>
  <img src="https://github.com/user-attachments/assets/eff33e23-8282-4f3c-a4e5-60f5ff722dc1" width="500">

<br>

**11. 최근 본 장소**
- Local Storage를 활용하여 최근 본 장소 목록 조회 가능
   <br>
  <img src="https://github.com/user-attachments/assets/a3acaaf8-6777-4335-bd51-107127a80837" width="400">
  <img src="https://github.com/user-attachments/assets/9ec52872-f1d1-4f1e-a9bc-eee631e8e52e" width="400">

<br>

**12. 멍생네컷**
- 프레임과 이미지 4장을 골라 멍생네컷 생성
- 이미지는 다운로드 및 공유 가능
- 나의 멍생네컷 목록과 전체 멍생네컷 목록 조회
 <br>
  <img src="https://github.com/user-attachments/assets/26849813-adcc-41cd-aa4e-d766e38b28a0" width="230">
  <img src="https://github.com/user-attachments/assets/04b02e95-2c74-4b40-a53d-bca7416e0b55" width="230">
  <img src="https://github.com/user-attachments/assets/b7a833f8-88fd-4f0e-8d19-66f4e5194599" width="230"> <br>
  <img src="https://github.com/user-attachments/assets/3b48ad9a-01b2-4442-be59-c3067f78a3b3" width="230">
  <img src="https://github.com/user-attachments/assets/e1bab160-b24c-4bd4-893c-6adb17fb2045" width="230">

  
<br/>
<br/>

## 프론트엔드 기술 고민! 
1. 이미지가 많아서 화면 로딩이 느려지는 현상
    - Intersection Observer를 활용한 무한 스크롤을 구현하여 필요한 만큼 데이터를 불러와 이미지 로딩 속도 최적화 <br/>

2. 고화질 이미지를 업로드 하는데 5초 넘게 걸리는 현상
    - Canvas API 및 OffscreenCanvas를 활용하여 이미지를 JPEG 또는 WebP 형식으로 압축 후 백엔드로 전송
    - 이를 통해 업로드 시간 5초에서 123ms로 대폭 개선 <br/>

3. 멍생네컷 생성 시 이미지가 줄어드는 현상
    - hmtl2canvas 라이브러리가 HTML 태그를 캡쳐할 때 대부분의 CSS 스타일을 지원하지만 object-fit: cover 속성을 제대로 처리하지 못하는 문제가 발생함.
    - 기존에는 이미지 업로드 후 css로 이미지가 꽉 차도록 하여 프레임에 맞게 비율을 조절하였으나, html2canvas를 호출하기 전 JavaScript로 이미지의 크기나 비율을 조정한 후 캡처하여 해결 <br/>
<br/>

## 백엔드 기술 고민!
1. 이미지를 넣으려 하는데 S3가 응답을 안한다면?
    - temp_file 테이블에 url, 멤버 정보와 함께 Blob 형식으로 이미지 임시 저장 후 서비스가 정상적으로 된다면 temp_file을 S3에 업로드 한 뒤 임시 이미지 삭제 <br/>

2. S3 업로드가 성공했는데 데이터베이스 작업 중 예외가 발생했다면?
    - S3에 업로드 된 파일이 남아있는 상황을 고려하여 데이터베이스 작업 중 예외가 발생하면 업로드 된 파일을 삭제하는 로직 추가 <br/>

<br/>

## 🖥️ Software Arichtecture 
![스크린샷 2024-12-19 135045](https://github.com/user-attachments/assets/da8a15c8-f025-4a3c-985d-34437012e3bd)


## 💡 Information Arichtecture
![IA (1)](https://github.com/user-attachments/assets/8c1b95da-f5e0-4770-9fc8-94528f609d78)


## 📜 ERD
![멍멍99](https://github.com/user-attachments/assets/5440b8cb-f3f5-45e5-a30f-16e919d47753) 
<br/>


## ⚒️기술 스택
### 📘 [Fronte-End]
- <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white"/> <img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=for-the-badge&logo=Tailwind CSS&logoColor=white"/> <img src="https://img.shields.io/badge/Zustand-black?style=for-the-badge&logo=Zustand&logoColor=F7D331"> <img src="https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=Yarn&logoColor=white">  <img src="https://img.shields.io/badge/MSW-171717?style=for-the-badge&logo=Chromatic&logoColor=FF6A33">  <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=Axios&logoColor=white">
- <img src="https://img.shields.io/badge/Vite-B050F6?style=for-the-badge&logo=Vite&logoColor=white"> <img src="https://img.shields.io/badge/Stroybook-FF4785?style=for-the-badge&logo=Storybook&logoColor=white"> <img src="https://img.shields.io/badge/Chromatic-FC521F?style=for-the-badge&logo=Chromatic&logoColor=white">
- <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white"/>
<br/>


**React**
- 사용자 인터페이스를 구축하기 위한 JavaScript 라이브러리로, 컴포넌트 기반 아키텍처를 통해 재사용성과 유지보수성을 높입니다.

**Tailwind CSS**
- 유틸리티 퍼스트 CSS 프레임워크로, 미리 정의된 클래스명을 사용하여 빠르고 효율적으로 스타일링할 수 있습니다. 커스터마이징이 용이하여 반응형 디자인에 적합합니다.

**Zustand**
- 경량 상태 관리 라이브러리로, React 애플리케이션의 상태를 간편하게 관리할 수 있도록 돕습니다. 간단한 API와 훅을 제공하여 개발자 경험을 개선합니다.

**Yarn**
- JavaScript 패키지 매니저로, 패키지 의존성을 관리하고 설치 속도를 개선합니다. npm보다 빠르고, 안정적인 설치를 지원하여 팀원 간의 일관성을 유지합니다.

**MSW (Mock Service Worker)**
- API 요청을 가로채고 모의 응답을 제공하여, 프론트엔드 개발 및 테스트를 용이하게 하는 라이브러리입니다. 실시간으로 API를 모킹할 수 있어 개발 과정에서 유용합니다.

**Axios**
- Promise 기반의 HTTP 클라이언트로, API와의 통신을 간편하게 처리할 수 있게 도와줍니다. 요청 및 응답을 쉽게 변환하고, 다양한 설정이 가능합니다.

**Vite**
- 빠른 빌드 및 개발 서버를 제공하는 차세대 프론트엔드 빌드 도구로, 핫 모듈 교체(HMR)가 지원되어 개발 속도를 크게 향상시킵니다. ES 모듈을 기반으로 하여 최적화된 번들링을 제공합니다.

**Storybook**
- UI 컴포넌트를 독립적으로 개발하고 문서화할 수 있는 도구로, 다양한 상태를 시각적으로 확인할 수 있게 해줍니다. UI 개발을 보다 효율적으로 진행할 수 있도록 지원합니다.

**Chromatic**
- Storybook과 통합되어 UI 컴포넌트의 시각적 변화를 관리하는 서비스로, 자동화된 시각적 테스트와 리뷰 기능을 제공합니다. 팀원 간의 협업을 개선하는 데 도움을 줍니다.

**JavaScript**
- 웹 개발의 핵심 프로그래밍 언어로, 클라이언트 측 및 서버 측에서 동작하며, 비동기 프로그래밍, DOM 조작, 이벤트 처리 등을 통해 인터랙티브한 웹 애플리케이션을 구축할 수 있습니다.
<br/>


### 📗 [Back-End]
- <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring Security&logoColor=white"> <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white">

- <img src="https://img.shields.io/badge/Spring Data Jpa-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"> <img src="https://img.shields.io/badge/Spring Data JDBC-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"> <img src="https://img.shields.io/badge/JooQ-000000?style=for-the-badge&logo=JWT&logoColor=white">

- <img src="https://img.shields.io/badge/Spring Batch-6DB33F?style=for-the-badge&logo=Spring&logoColor=white">

- <img src="https://img.shields.io/badge/Mahout-D22128?style=for-the-badge&logo=apache&logoColor=white">

- <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/redis-FF4438?style=for-the-badge&logo=redis&logoColor=white">

- <img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=for-the-badge&logo=Amazon EC2&logoColor=white"> <img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=for-the-badge&logo=Amazon RDS&logoColor=white"> <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white"> <img src="https://img.shields.io/badge/Amazon ELB-8C4FFF?style=for-the-badge&logo=Amazon Elastic Load Balancing&logoColor=white">
<br/>


**Spring Security**
- 애플리케이션의 인증과 권한 관리를 구현하기 위한 보안 프레임워크입니다.

**JWT (JSON Web Token)**
- 사용자 인증 정보를 안전하게 주고받을 수 있는 토큰 기반 인증 방식입니다.

**Spring Data JPA**
- 테이블을 객체로 매핑해 쿼리를 자동으로 생성하며, 복잡한 관계를 효율적으로 처리합니다.

**Spring Data JDBC**
- Batch 처리 등 대량 데이터 삽입 작업을 빠르고 간단하게 수행할 수 있습니다.

**Spring Batch**
- 대용량 데이터를 효율적으로 처리하기 위한 배치 프로세싱 프레임워크입니다.

**JOOQ**
- 동적 쿼리를 작성하고 데이터베이스 작업을 유연하게 처리하기 위해 사용됩니다.

**Mahout**
- 기계 학습 기반의 라이브러리로, 추천 시스템에서 협업 필터링을 구현할 때 활용됩니다.

**AWS EC2**
- 스프링 애플리케이션을 배포하기 위한 서버입니다.

**RDS (MySQL)**
- 안정적인 데이터 관리를 위한 데이터베이스 서버입니다.

**Redis**
- 캐싱을 통해 빠른 데이터 조회와 고성능 처리를 지원합니다.

**S3**
- 파일 저장 및 관리를 위한 객체 스토리지 서비스입니다.

**ELB (Elastic Load Balancer)**
- 애플리케이션 서버의 트래픽을 분산 처리하여 가용성과 안정성을 높입니다.
<br/>



### 📕 Co-Working-Tool
- <img src="https://img.shields.io/badge/Github-black?style=for-the-badge&logo=Github&logoColor=white"/> <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=Jira&logoColor=white">
- <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=Discord&logoColor=white"/> <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white"/> <img src="https://img.shields.io/badge/Notion-black?style=for-the-badge&logo=Notion&logoColor=white"/>  <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white"> <img src="https://img.shields.io/badge/Zoom-0B5CFF?style=for-the-badge&logo=Zoom&logoColor=white">
<br/>


## 🗂️ Convention
### Branch Architecture
master: 배포가 되는 브랜치 <br/>
develop: 배포전 임시<br/>
KAN-[number]: Jira 스토리 번호<br/>

### 생성되는 jira branch 이름
![Group 39659](https://github.com/user-attachments/assets/f9db5dff-116c-4bf4-a234-09e0f8ba4a67)

### Commit 
<b> Commit Format </b>
Type: content

```
feat: Seo 기능 추가

feat: Header 스타일 추가

git commit -m "feat: "
```

**Commit Type**
| 타입         |설명                                                           | 예시                                                  |
| ------------ | -------------------------------------------------------------- | ----------------------------------------------------- |
| **feat**     | 새로운 기능을 추가할 때 사용합니다.                            | `feat: 로그인 폼 유효성 검사 추가`                 |
| **fix**      | 버그를 수정할 때 사용합니다.                                   | `fix: 로그인 버그 수정`                            |
| **style**    | 사용자 인터페이스 관련 변경 사항.                              | `style: 네비게이션 바 디자인 수정`                 |
| **refactor** | 버그 수정이나 기능 추가 없이 코드 구조를 개선할 때 사용합니다. | `refactor: 컴포넌트 상태 관리 로직 단순화`         |
| **perf**     | 성능을 개선하는 코드 변경.                                     | `perf: 이미지 로딩 시간 최적화`                   |
| **test**     | 테스트 코드를 추가하거나 수정할 때 사용합니다.                 | `test: 버튼 컴포넌트에 대한 단위 테스트 추가`      |
| **docs**     | 문서만 변경할 때 사용합니다.                                   | `docs: 설치 단계 README에 추가`                    |
| **chore**    | 소스나 테스트 파일을 수정하지 않는 일반적인 작업이나 업데이트. | `chore: 종속성 패키지 업데이트`                    |
| **revert**   | 이전 커밋을 되돌릴 때 사용합니다.                              | `revert: "로그인 폼 유효성 검사 추가" 커밋 되돌림` |
| **init**     | 프로젝트 초기 설정 시 사용합니다.                              | `init: React 프로젝트 초기 설정`                   |
| **delete**   | 코드/파일 삭제.                                                | `delete: 안 쓰는 로그인 컴포넌트 삭제`             |
| **wip**      | 작업 중이거나 실험적인 변경 사항.                              | `wip: 새로운 인증 방법을 실험 중`                  |

### Pull Request
**Description**

```
## 작업 내용

- 작업 내용 1
- 작업 내용 2

## 이슈
- 어떤 이슈가 있는지 작성

## 참고

- 구현한 화면이나 영상
- bug fix면 어떻게 해결했는지
```


