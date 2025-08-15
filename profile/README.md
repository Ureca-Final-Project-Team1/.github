# <div align="center">수탁형 C2C 데이터 거래 플랫폼, UFO-Fi🛸</div>

<div align="center"><img src='https://github.com/Ureca-Final-Project-Team1/UFO-Fi-FE/raw/develop/docs/readme/thumnail.svg' widtj='120' /></div>

<div align="center">


<p>
지금 지구는요…<br>
남는 데이터는 매달 <strong>소멸</strong>되고,<br>
부족할 땐 <strong>비싼 요금</strong>으로 충전하며,<br>
비공식 거래는 <strong>불안과 위험</strong>을 안고 있습니다.
</p>

<p>
그래서 등장했습니다 – <strong>UFO-Fi!</strong>
</p>

<p>
👽 <strong>외계에서 온 신뢰의 데이터 중개사, 유포파이(UFO-Fi)</strong>는<br>
여러분의 데이터를 <strong>안전하게 보관</strong>하고,<br>
필요한 사람에게 <strong>간편하게 전달</strong>해줍니다.
</p>


[서비스 바로가기](https://www.ufo-fi.store) | [Storybook](https://686aad151c7964b9495b4f40-mjroypvwoa.chromatic.com/?path=/docs/ui-chip--docs) | [기획안](https://docs.google.com/document/d/18lT4sulS8pPTNh95n2JUIQZff5S-SvHB/edit?usp=sharing&ouid=101077923369398316818&rtpof=true&sd=true)

**시연 영상**

[![시연 영상](https://img.youtube.com/vi/tK7f2OSCOx0/0.jpg)](https://www.youtube.com/watch?v=tK7f2OSCOx0)

</div>

## 프로젝트 개요

| 항목           | 내용                             |
| -------------- | -------------------------------- |
| **프로젝트명** | UFO-Fi                           |
| **팀명**       | AL1EN                            |
| **주제**       | 무선 데이터 용량 공유 플랫폼          |
| **타겟층**     | 데이터 구매 수요 및 공급층       |
| **개발 기간**  | 2025.06.30 ~ 2025.08.07 (약 5주) |

## 서비스 소개

> **UFO-Fi**는 수탁형 구조를 기반으로 한 유휴 모바일 데이터 C2C 거래 플랫폼입니다.

- **문제 인식**
  - **유휴 데이터의 구조적 소멸**: 무제한 요금제 확산으로 과잉 제공된 데이터의 자동 소멸 현상
  - **비공식 거래의 신뢰성 문제**: 중고 커뮤니티 기반 거래의 사기 위험성과 법적 보호의 부재
  - **공식 유통 채널의 부재**: 통신사 데이터 선물 기능의 낮은 사용성과 거래 수단으로서의 한계
- **우리의 해결책**
  - **수탁 구조**를 통해 플랫폼이 제3자로서 데이터와 ZET를 안전하게 중개합니다.

## Project Architecture

**시스템 아키텍처**

![system](https://github.com/Ureca-Final-Project-Team1/UFO-Fi-FE/raw/main/docs/readme/system-arch.png)

**인프라 아키텍처**

![if](https://github.com/Ureca-Final-Project-Team1/UFO-Fi-FE/raw/main/docs/readme/infra-arch.png)



## 기술 스택

| 분야                               | 기술 스택                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Frontend**                       | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white) ![Zustand](https://img.shields.io/badge/Zustand-FF6B35?style=flat&logo=zustand&logoColor=white) ![React Query](https://img.shields.io/badge/React_Query-FF4154?style=flat&logo=reactquery&logoColor=white) ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=axios&logoColor=white)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Frontend UI/UX & Testing**       | ![Shadcn/ui](https://img.shields.io/badge/Shadcn%2Fui-000000?style=flat&logo=shadcnui&logoColor=white) ![Storybook](https://img.shields.io/badge/Storybook-FF4785?style=flat&logo=storybook&logoColor=white) ![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat&logo=eslint&logoColor=white) ![Prettier](https://img.shields.io/badge/Prettier-F7B93E?style=flat&logo=prettier&logoColor=black) ![Husky](https://img.shields.io/badge/Husky-42B883?style=flat&logo=husky&logoColor=white)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Backend**                        | ![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat&logo=springsecurity&logoColor=white) ![OAuth2](https://img.shields.io/badge/OAuth2-4285F4?style=flat&logo=oauth&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=JSON%20web%20tokens&logoColor=white) ![JPA](https://img.shields.io/badge/JPA-59666C?style=flat&logo=hibernate&logoColor=white) ![QueryDSL](https://img.shields.io/badge/QueryDSL-0078D4?style=flat&logo=java&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white) ![FCM](https://img.shields.io/badge/FCM-FFCA28?style=flat&logo=firebase&logoColor=black)                                                                                                                                              |
| **Backend Testing & Code Quality** | ![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=flat&logo=junit5&logoColor=white) ![Mockito](https://img.shields.io/badge/Mockito-25A162?style=flat&logo=mockito&logoColor=white) ![H2](https://img.shields.io/badge/H2-0078D4?style=flat&logo=h2&logoColor=white)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Infrastructure**                 | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white) ![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat&logo=amazon-ec2&logoColor=white) ![AWS RDS](https://img.shields.io/badge/AWS_RDS-527FFF?style=flat&logo=amazon-rds&logoColor=white) ![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat&logo=amazon-s3&logoColor=white) ![AWS VPC](https://img.shields.io/badge/AWS_VPC-FF4F00?style=flat&logo=amazon-aws&logoColor=white) ![Route 53](https://img.shields.io/badge/Route_53-DA7B00?style=flat&logo=amazon-route-53&logoColor=white) ![AWS ACM](https://img.shields.io/badge/AWS_ACM-FF9900?style=flat&logo=amazon-aws&logoColor=white) ![AWS IAM](https://img.shields.io/badge/AWS_IAM-DD344C?style=flat&logo=amazon-aws&logoColor=white) ![ElastiCache](https://img.shields.io/badge/ElastiCache-C925D1?style=flat&logo=amazon-aws&logoColor=white) |
| **Development Tools**              | ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white) ![Google Drive](https://img.shields.io/badge/Google_Drive-4285F4?style=flat&logo=googledrive&logoColor=white) ![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat&logo=discord&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=swagger&logoColor=black) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)                                                                                                                                                                                                                                                                                                                                                                      |

## **주요 기능**

| 항목 | 내용 |
| --- | --- |
| **회원 인증 및 사용자 시스템** | **Kakao OAuth2 소셜 로그인**<br>OAuth2 인증 후 자체 JWT + Refresh Token 발급<br><br>**요금제 자동 등록**<br>명세서 OCR 분석<br><br>**마이페이지**<br>요금제·계좌 관리, 거래 내역, 업적 시스템 제공 |
| **ZET 충전 및 PG 결제 시스템** | **ZET(Zero Expired Traffic)**<br>내부 재화 (1ZET = 10원)<br><br>**Toss Payments** 연동 → 실시간 카드 결제 및 ZET 충전<br><br>**충전 상태 FSM 관리**<br>(요청 → 대기 → 성공/실패)<br><br>**보안 강화 + 예외 처리 UX 반영** |
| **데이터 거래 시스템 (수탁형 구조)** | **판매자**<br>통신사·용량·가격 입력 후 데이터 등록<br><br>**구매자**<br>전화번호 입력 → 플랫폼이 대신 전송 _(통신사 선물 기능 활용)_<br>판매 시점 잔여량 자동 차감 + ZET 자동 정산<br><br>**3단계 UI**<br>데이터 등록 → 구매 요청 → 수령 확인<br><br>**일괄구매 기능**<br>예산/용량 기반 최적 조합 탐색 + 일부 구매 가능 |
| **운영 모니터링 및 관리자 백오피스** | **Slack Webhook 연동**<br>결제 실패, 트래픽 급증 자동 알림<br><br>**신고/제재 시스템**<br>자동 누적 차단 + 관리자 수동 처리<br><br>**금칙어 관리**<br>아호코라식 필터링, 사용자 정지/해제, ZET 복구 기능 포함<br><br>**운영 대시보드**<br>사용자/게시글/거래/신고 통계 실시간 시각화 |
| **신뢰 기반 사용자 참여 시스템** | **팔로우 추천 시스템**<br>Qdrant 기반 유사·보완 사용자 자동 매칭<br><br>**FCM 푸시 알림**<br>거래 성사, 신고 결과 등 실시간 알림 제공<br><br>**전파 거리 시각화**<br>BFS 기반으로 판매자 ↔ 구매자 연결 깊이 최대 5단계 추적<br><br>**우주 편지 생성**<br>전파 단계마다 AI 편지 생성 및 업적 달성 보상 |


## 팀원 소개 및 역할

| 프로필                                                                                | 이름                                                                | 주요 역할 및 기여                                                                |
| ---------------------------------------------------------------------------------- | ----------------------------------------------------------------- | ------------------------------------------------------------------------- |
| <img src="https://avatars.githubusercontent.com/u/165022381?v=4" width="80"/>      | **송현규**<br>[@songhyeongu](https://github.com/songhyeongu)         | `BE 리드`<br>- 전체 DB/ERD 설계<br>- 거래/정산 로직, 성능 최적화<br>- ZET 기반 포인트 시스템 구현   |
| <img src="https://avatars.githubusercontent.com/Jeong-Minkyeong?s=80" width="80"/> | **정민경**<br>[@Jeong-Minkyeong](https://github.com/Jeong-Minkyeong) | `BE`<br>- 인증/보안 로직 담당<br>- 알림, 관리자 대시보드 API 개발                           |
| <img src="https://avatars.githubusercontent.com/chungjeongsu?s=80" width="80"/>    | **정지호**<br>[@chungjeongsu](https://github.com/chungjeongsu)       | `BE`<br>- 사용자/상품 CRUD API<br>- 거래/매칭 로직 구현                               |
| <img src="https://github.com/abyss-s.png" width="80"/>                             | **이영주**<br>[@abyss-s](https://github.com/abyss-s)                 | `팀 리드`, `FE 리드`<br>- 프로젝트 구조 설계 및 총괄<br>- 판매글 등록, 일괄구매, FSM 기반 상태관리 구현 |
| <img src="https://github.com/dogeonkim1.png" width="80"/>                          | **김도건**<br>[@dogeonkim1](https://github.com/dogeonkim1)           | `FE`<br>- ZET 충전 및 결제 로직<br>- 관리자 백오피스, Storybook 문서화     |
| <img src="https://github.com/minji-38.png" width="80"/>                            | **안민지**<br>[@minji-38](https://github.com/minji-38)               | `FE`<br>- 데이터 구매 UX 흐름 구현<br>- 전파거리 시각화, 마이페이지 UI/UX         |
| <img src="https://github.com/kuru2141.png" width="80"/>                            | **진영호**<br>[@kuru2141](https://github.com/kuru2141)               | `FE`<br>- 소셜 로그인/JWT 인증<br>- GPT 기반 추천 및 감성 메시지 시스템 개발           |


---

Team AL1EN | LG U+ URECA SW교육과정 2기 최종융합프로젝트 1조
