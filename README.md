👨‍💻 Portfolio
Full Stack · Android(AOSP) · IoT · Embedded Engineer
📌 About Me

Full Stack 개발 (Web · Mobile · Server)

AOSP 기반 디바이스/로봇 시스템 개발

IoT 통신(BLE/Wi-Fi) 및 공간 연산(JTS)

C 기반 지도 변환기 및 임베디드 네비게이션 개발

PM 경험 다수 (기획 ~ 설계 ~ 개발 ~ 운영 안정화)

🚀 Projects
8. 📚 도서관 정보 서비스 (Full Stack)

Period: 2026.01 ~ Present
Role: Full Stack Developer (Personal Project)
Tech Stack:
Astro · TypeScript · Fastify · Supabase · Expo (React Native) · Cloudflare Pages · GPT-4o-mini

🔹 Overview

공공도서관 API 기반 AI 도서 추천 및 위치 기반 도서 검색 서비스.
Web + Android/iOS 앱을 동시에 제공하는 멀티 플랫폼 구조.

🔹 Architecture
Cloudflare Pages (Astro Web)
        ↓
      Fastify (VPS API Server)
        ↓
      Supabase (DB/Auth/RLS)

Expo React Native (Mobile)
        ↓
     Same API Server
🔹 Key Features

공공도서관 API 기반 도서 검색 및 베스트셀러 조회

AI 도서 추천 및 인사이트 요약

GPS 기반 근처 도서관 보유 현황 검색

회원 서재(찜) 기능

한줄평 작성/조회

Web + Android/iOS 동시 제공

🔹 Core Implementation

Supabase JWT 서버 검증 기반 인증 보안 강화

Rate Limiting / CORS / RLS 적용

getAuthHeader() 패턴 기반 토큰 자동 갱신

Monorepo 구조로 Web / Mobile / Server 통합 관리

🔹 Troubleshooting

Astro define:vars IIFE 래핑 → GA4 전역 스코프 누락 → set:html 방식으로 해결

Cloudflare Pages 환경변수 빌드 타임 주입 이슈 해결

JWT 리팩토링 후 프로필 수정 팝업 빈 데이터 버그 수정

7. 🏨 이스트라 – Room매니저 Web Full Stack

Period: 2025.02 ~ 2025.10
Team: 4
Role: PM / Frontend Lead
Tech: AOSP · Vue.js (Quasar, Vite) · PHP · MySQL · JWT

🔹 Overview

호텔/숙박 환경을 위한 Web · Android · TV 런처 통합 관리 시스템 개발.

🔹 Key Contributions
1️⃣ 멀티 플랫폼 아키텍처 설계

관리자 Web 콘솔 및 결제 페이지

Android 관리자 앱

AOSP 기반 TV 런처(WebView)

통합 인증 구조 설계

2️⃣ TV 리모컨 브릿지 구현

Native KeyEvent → Web Focus 전달

리모컨 UX 최적화 로직 설계

3️⃣ 인증 고도화

Axios Interceptor 기반 401 자동 재발급

Refresh Queue 패턴으로 race condition 방지

4️⃣ 글로벌 결제 시스템

주문 UUID 기반 트랜잭션 설계

Alipay / WeChat PG 분기 처리

결제 재시도 플로우 설계

6. 🌬 SK매직 – 공기청정기 App

Period: 2025.05 ~ 2025.06
Team: 6
Role: Android Developer
Tech: Kotlin · Jetpack Compose · BLE · AWS Cognito · JTS · OpenCV · NDK

🔹 Key Contributions
IoT 연동

BLE GATT 기반 프로비저닝

AES 기반 Wi-Fi 연결 프로세스

AQM / 로봇청정기 통합 제어

공간 연산

JTS 기반 SLAM 지도 폴리곤 분할/병합

Geometry 유효성 복원 알고리즘

보안 강화

NDK 암복호화 루틴

루팅/디버깅 탐지

AlarmManager 기반 자동 재기동

5. 💄 뷰티망고 – Full Stack

Period: 2024.05 ~ 2025.01
Team: 4
Role: PM / Backend & App Lead
Tech: Flutter · Spring Boot · MariaDB · JWT · AWS S3

🔹 Key Contributions

Flutter 기반 Android/iOS 동시 배포

Spring Boot 계층형 아키텍처 설계

REST API 및 DB 스키마 설계

PortOne 결제 연동

FCM 푸시 시스템 구축

Clean Architecture + Riverpod 적용

4. 🤖 클로봇 – 박물관 큐레이팅 로봇

Period: 2022.05 ~ 2024.12
Team: 6
Role: PM / Android Developer
Tech: AOSP · Kotlin

🔹 Key Contributions

LG CLOI 기반 안내 시스템 개발

다국어 콘텐츠 연동 시스템 구축

인터랙티브 퀴즈/퍼즐 기능 구현

크래시 로그 자동 전송 핸들러

FTP 기반 원격 APK 업데이트 시스템

3. 📅 Wemet – 일정 관리 시스템

Period: 2022.01 ~ 2022.04
Team: 2
Role: PM / Backend
Tech: Node.js · MongoDB · TypeScript

일정 관리 REST API 서버 구축

MongoDB 스키마 설계

TypeScript 기반 구조 설계

2. 🗺 오토에버 – 해외지도 변환기

Period: 2021.11 ~ 2022.12
Team: 3
Role: PM & 변환기 개발
Tech: C · MFC · SQLite3 · MSSQL

해외 원도 데이터를 센터맵 포맷으로 변환

검증 Viewer 개발

통계 DB 및 검증 DB 생성

CodeSonar 대응

1. 🚗 M&N Soft – 6세대 네비게이션 EngineApp

Period: 2018.10 ~ 2021.10
Team: 10
Role: PM / 지도 파트 개발
Tech: C · Linux · Embedded

MCOLS 이슈 해결

지도 파트 신규 기능 개발

Base Component 연동

CCOS API 설계 및 확장

🧠 Core Competencies
✔ Full Stack Development

Vue · Flutter · React Native · Spring Boot · Node.js · Fastify

✔ Embedded & AOSP

Linux · C · AOSP · Device Integration

✔ IoT & Robotics

BLE · Wi-Fi · SLAM · JTS Geometry Processing

✔ Security & Architecture

JWT · RLS · Rate Limiting · NDK Security · Clean Architecture
