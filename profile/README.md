# 🐔 Blind Chicken Market

익명 기반 중고 경매 거래 플랫폼 (Full-Stack Project)

> **Blind Chicken Market**은 사용자가 익명으로 중고 상품을 등록하고, 입찰(경매) 또는 구매할 수 있는 웹 플랫폼입니다.
> 또한 Admin 서비스 제공을 통해 서비스의 전반적인 부분을 관리하는 기능 또한 제공합니다.
> 실무형 풀스택 경험을 목표로, 프론트엔드부터 백엔드, 배포까지 모두 구현합니다.

---

## 🚀 프로젝트 개요

| 항목       | 내용                                                |
| ---------- | --------------------------------------------------- |
| 프로젝트명 | Blind Chicken Market                                |
| 주제       | 익명 기반 중고 거래 및 경매 웹사이트                |
| 개발 기간  | 2025.10.31 ~ 2026.01.07                              |
| 목표       | 프론트엔드 + 백엔드 통합 전자상거래 프로토타입 완성 |
| 팀명       | Darius Team                                         |
| 배포 주소  | https://bcm.u-jinlee1029.store/                                         |

---

## 🧩 주요 기능

### ✅ 필수 기능

- 반응형 웹 디자인 (PC / 모바일)
- RESTful API 설계 및 구현
- Admin 페이지
- 상품 등록 / 수정 / 삭제 / 조회 (CRUD)
- 사용자 회원가입 및 로그인 (NextAuth)
- 데이터베이스 연동
- TypeScript를 활용한 타입 안정성 확보

---

## 🧱 기술 스택

| 구분                | 사용 기술                                                  |
| ------------------- | ---------------------------------------------------------- |
| Frontend            | Next.js, TypeScript, Tailwind CSS, shadcn/ui, Axios        |
| Backend             | Spring Boot, STOMP (WebSocket), JPA (Java Persistence API) |
| DB                  | PostgreSQL, Redis(NoSQL)                                   |
| Server / Deployment | AWS EC2, Route53 / Caddy, CI/CD(Github Actions)           |

---

## 🪜 개발 목표

- UI/UX 설계 및 반응형 구현
- RESTful API 설계 및 DB 구축
- 인증 / 권한 / 세션 관리
- 상품 등록 → 입찰 → 낙찰 → 결제 까지의 흐름 완성
- TypeScript로 안정적 코드베이스 유지

---

## 🧾 문서화

| 항목         | 설명                                                                                  |
| ------------ | ------------------------------------------------------------------------------------- |
| README       | 프로젝트 개요 및 실행 방법                                                            |
| API 문서     | https://bcm.u-jinlee1029.store/swagger-ui/index.html |
| ERD          | https://www.erdcloud.com/                                                             |
| 와이어프레임 | v0.dev 디자인 시안 https://v0.app/chat/blind-chicken-market-spaJeozaobA               |
| 시연 영상    | (추후 추가)                                                                           |

---

## 🧑‍💻 팀 정보

| 이름   | 역할          | 담당                                                                                |
| ------ | ------------- | ----------------------------------------------------------------------------------- |
| 이유진 | PM / DevOps | 서버 구축 및 CI/CD 구축 |
| 남경진 | Frontend       | 프로젝트 서비스 기능 고도화                      |
| 유민기 | Frontend        | 프로젝트 어드민 구현 및 고도화                                                 |
| 김세헌 | Backend      | 어드민 페이지 API 구현 및 통계 API 구현                                    |
| 한성우 | Backend      | QnA 및 자주묻는 질문 관련 API 구현                                    |

---

## 🧹 Code Style

- 코드 포맷: **Prettier**
- 코드 규칙 검사: **ESLint**
- 저장 시 자동 정리 기능 활성화 (VSCode 권장)

---

## 🔖 참고 자료

- Tailwind CSS 설치 및 클래스
  https://tailwindcss.com/docs/installation/using-vite

- Shadcn/ui
  https://ui.shadcn.com/docs/installation/next
