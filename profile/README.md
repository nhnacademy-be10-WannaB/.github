# WannaB 📚

> NHN ACADEMY 최종 프로젝트 <br>
> 도서 쇼핑 사이트
### Wannab 도메인
[📎 WannaB](https://wannab.shop/)

## 📜 목차
- [🗓️ 프로젝트 개요](#프로젝트-개요)
  - [진행 기간](#진행-기간)
  - [팀 구성](#팀-구성-)
- [📢 서비스 소개](#서비스-소개)
- [🥳 서비스 설계](#서비스-설계)
  - [기술 스택](#기술-스택)
  - [ERD](#erd)
  - [Wireframe](#wireframe)
  - [Architecture](#architect)
  - [Docs](#docs)
- [🤗 기능 소개](#-기능-소개)
- [😆 느낀점](#-느낀점)

## 🗓️ 프로젝트 개요

### 진행 기간

- 2025.06.09 ~ 2025.07.25 (7주)
<br>

## 팀 구성 🔥
|             [고충원](https://github.com/won-ee)              |             [김동균](https://github.com/dkyun97)              |              [김영대](https://github.com/yeong-dae)              |             [김훈민](https://github.com/gnsals0904)              |
|:---------------------------------------------------------:|:----------------------------------------------------------:|:-------------------------------------------------------------:|:--------------------------------------------------------------:|
| <img width="130px" src="https://github.com/won-ee.png" /> | <img width="130px" src="https://github.com/dkyun97.png" /> | <img width="130px" src="https://github.com/yeong-dae.png" /> | <img width="130px" src="https://github.com/gnsals0904.png" /> |
|                  Front, CI/CD, 도서 서비스                   |                  결제, 쿠폰 서비스                             |                       도서 서비스                               |      팀장, CI/CD, 도서 서비스                                      |

|            [박지후](https://github.com/jihoo1214)            |             [양재원](https://github.com/yang-jaewon)              |             [임재은](https://github.com/LimJaeEun0930)              |             [정민수](https://github.com/Minsooooooo)              |
|:---------------------------------------------------------:|:----------------------------------------------------------:|:--------------------------------------------------------------:|:--------------------------------------------------------------:|
| <img width="130px" src="https://github.com/jihoo1214.png" /> | <img width="130px" src="https://github.com/yang-jaewon.png" /> | <img width="130px" src="https://github.com/LimJaeEun0930.png" /> | <img width="130px" src="https://github.com/Minsooooooo.png" /> |
|                            회원 서비스                         |                         회원 서비스                             |                         주문 서비스, 장바구니 서비스                        |                             주문 서비스                                |



<br>

## 서비스 소개
- 동영상 삽입

<br>

## 서비스 설계
### 기술 스택
### 주요 기술 스택

| **구분** | **Frontend** | **Backend** |
| --- | --- | --- |
| **Language** | HTML, CSS | Java **21** |
| **IDE** | IntelliJ | IntelliJ |
| **Framework** | - | Spring Boot, Spring Security, Spring Web, Spring JPA, Spring Cloud (Gateway, Config, OpenFeign, Eureka), Spring AOP, Spring Session Redis |
| **Library** | Tailwind CSS | jjwt, Lombok, OpenFeign, Spring Validation (Jakarta), Spring Mail, Commons DBCP2, QueryDSL, Spring REST Docs, RabbitMQ, Actuator |
| **Template** | Thymeleaf | - |

### 공통 기술 스택

| **구분** | **기술** |
| --- | --- |
| **DB** | MySQL, Redis, H2 |
| **Infra** | GitHub Action, Docker, Nginx, Elasticsearch, RabbitMQ, Eureka, Config Server, MinIO |
| **Tools** | GitHub, Notion, Dooray, Wiki |
| **Build** | Maven, Spring Boot Maven Plugin, **APT Plugin**, Asciidoctor, Spring Configuration Processor, **JaCoCo (Test Coverage)** |
| **Test** | Spring Boot Test, Spring Security Test, Spring REST Docs, Spring Rabbit Test, Spring Cloud Contract Stub Runner |

### CI/CD
<img width="2772" height="636" alt="Group 1" src="https://github.com/user-attachments/assets/af60b58f-aa5e-4756-ac24-c40b5c829e07" />


### ERD
[📎 Wannab ERD 구조도](https://www.erdcloud.com/d/pxzhyqs65xYJiXHvJ)

### Architect
[📎 Wannab 아키텍쳐 구조도](https://github.com/nhnacademy-be10-WannaB/WannaB-wiki/wiki/Wannab-Architecture)

### Wireframe

[📎 Figma Link](https://www.figma.com/community/file/1529710551736698846)

### Docs
[📎 WannaB Team wiki](https://github.com/nhnacademy-be10-WannaB/WannaB-wiki/wiki)

## 🤗 기능 소개
<!-- TODO: 기능 소개 작성 -->
### **🏗️  인프라**

- 담당자 : 고충원, 김훈민
    - CI/CD
    - NHN CLOUD 기반 배포
    - Docker를 활용한 컨테이너화
    - Nginx를 활용한 로드 밸런싱 및 리버스 프록시 설정

### **🖥️  프론트(figma ,html, css)**

- 담당자 : 고충원
    - 피그마 및 html,css 구현

### **👤 회원**

- 담당자: 박지후, 양재원
    - jwt인증 : 박지후
    - oauth2 : 양재원

### 👑 **등급**

- 담당자: 양재원
    - 회원 등급 변경, 휴면 전환

### **📮 주소**

- 담당자: 박지후

### **💰포인트**

- 담당자: 박지후, 양재원

### **📝 리뷰**

- 담당자: 고충원
    - 도서별 리뷰 상세페이지 구현
    - 회원별 리뷰 상세페이지 구현
    - 리뷰 CRUD 구현

### **🎟️ 쿠폰**

- 담당자: 김동균

### **📖 도서**

- 담당자: 고충원, 김훈민
    - 도서 조회, 등록, 수정, 삭제 기능 구현
    - 도서 정렬(최신순, 제목순, 가격순) 기능 구현
    - 알라딘 API 기반 도서 등록 구현

### **🔍 검색**

- 담당자: 김훈민

### **☑️ 카테고리**

- 담당자: 김훈민, 김동균

### **❤️좋아요**

- 담당자: 고충원
    - 좋아요 CRUD 구현
    - 회원별 좋아요 내역 페이지 구현

### **📱 주문**

- 담당자: 임재은, 정민수
    - 회원 및 비회원 주문 기능 구현
    - 서버가 여러개인 경우 고려하여 레디스에 주문관련 정보 임시저장
    - 결제 완료 및 트랜잭션 커밋 이후 이벤트리스너를 통해 유저 포인트 차감/적립, 쿠폰처리, 도서재고 차감 비동기요청 RabbitMQ이용하여 구현
    - 회원 비회원 주문 조회 구현
    - 환불, 취소 기능 구현 및 그에 따른 포인트 롤백
    - 주문 상태변경 및 스케줄러를 활용한 TTL 구현
    - 주문-결제까지 완료시 SMTP이메일전송 이벤트 처리

### **🛒 장바구니**

- 담당자: 임재은
    - 회원 및 비회원의 장바구니 상품 추가, 수량변경, 삭제기능 구현
    - Redis 활용 및 회원의 경우 데이터베이스에 장바구니 영구저장되도록 구현

### **💳  결제**

- 담당자: 김동균

### 🛍️ **포장지**

- 담당자: 정민수
    - CRUD 구현

### **🚚 배송**

- 담당자 :정민수
    - 배송비 정책 CRUD 구현

### 💾 **파일**

- 담당자: 고충원
    - Minio 를 이용하여 image 저장, 호출

## 😆 느낀점
<!-- TODO: 개인 느낌점 작성 -->
<table border="1" cellspacing="0" cellpadding="10">
  <!-- 고충원 -->
  <tr>
    <th rowspan="3">
      <a href="https://github.com/won-ee">고충원</a><br />
      <img width="130px" src="https://github.com/won-ee.png" /><br />
      Front, CI/CD, 도서 서비스
    </th>
    <td colspan="2" rowspan="3"></td>
  </tr>
  <tr></tr>
  <tr></tr>

  <!-- 김동균 -->
  <tr>
    <th rowspan="3">
      <a href="https://github.com/dkyun97">김동균</a><br />
      <img width="130px" src="https://github.com/dkyun97.png" /><br />
      결제, 쿠폰 서비스
    </th>
    <td colspan="2" rowspan="3"></td>
  </tr>
  <tr></tr>
  <tr></tr>

  <!-- 김영대 -->
  <tr>
    <th rowspan="3">
      <a href="https://github.com/yeong-dae">김영대</a><br />
      <img width="130px" src="https://github.com/yeong-dae.png" /><br />
      도서 서비스
    </th>
    <td colspan="2" rowspan="3"></td>
  </tr>
  <tr></tr>
  <tr></tr>

  <!-- 김훈민 -->
  <tr>
    <th rowspan="3">
      <a href="https://github.com/gnsals0904">김훈민</a><br />
      <img width="130px" src="https://github.com/gnsals0904.png" /><br />
      팀장, CI/CD, 도서 서비스
    </th>
    <td colspan="2" rowspan="3"></td>
  </tr>
  <tr></tr>
  <tr></tr>

  <!-- 박지후 -->
  <tr>
    <th rowspan="3">
      <a href="https://github.com/jihoo1214">박지후</a><br />
      <img width="130px" src="https://github.com/jihoo1214.png" /><br />
      회원 서비스
    </th>
    <td colspan="2" rowspan="3"></td>
  </tr>
  <tr></tr>
  <tr></tr>

  <!-- 양재원 -->
  <tr>
    <th rowspan="3">
      <a href="https://github.com/yang-jaewon">양재원</a><br />
      <img width="130px" src="https://github.com/yang-jaewon.png" /><br />
      회원 서비스
    </th>
    <td colspan="2" rowspan="3"></td>
  </tr>
  <tr></tr>
  <tr></tr>

  <!-- 임재은 -->
  <tr>
    <th rowspan="3">
      <a href="https://github.com/LimJaeEun0930">임재은</a><br />
      <img width="130px" src="https://github.com/LimJaeEun0930.png" /><br />
      주문 서비스
    </th>
    <td colspan="2" rowspan="3"></td>
  </tr>
  <tr></tr>
  <tr></tr>

  <!-- 정민수 -->
  <tr>
    <th rowspan="3">
      <a href="https://github.com/Minsooooooo">정민수</a><br />
      <img width="130px" src="https://github.com/Minsooooooo.png" /><br />
      주문 서비스
    </th>
    <td colspan="2" rowspan="3"></td>
  </tr>
  <tr></tr>
  <tr></tr>
</table>
