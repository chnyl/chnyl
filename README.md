<div align="center">
  <h2> 👋 Welcome to CNYL Labs! </h2></div>
<br/>

### 🌟 About Me

  <h3> "Technical Generalist focused on building scalable systems and driving value creation." </h3>

- ✨ 스케일 가능한 **자동화 시스템** 및 **가치 창출 구조** 구축
- 🤖 **AI Coding & Building**: `Google Antigravity`, `OpenClaw`, `Vercel` 등 활용한 AI Coding 및 프로덕트 개발 진행
- 📊 **Data Analysis**: `Google BigQuery`, `Apache Superset` BI 툴을 통해 `SQL`과 `Python` 자유롭게 활용하여 인사이트 도출
- 🎨 **Visualization**: 15개 이상 PPT 단축키 사용, 벡터 이미지 편집 능력
- 🤝 **Partnership**: 국내/외 글로벌 대기업 파트너십

---

### 🚀 My Projects

#### 💌 [모바일 청첩장](https://github.com/chnyl/wed_invi_sharing) ('26.3 배포 완료)

> **하루 만에 완성한 프리미엄 반응형 웹 모바일 청첩장** (React 19 + TypeScript 기반)

- **주요 빌드 히스토리**: **Antigravity**와 **Kimi** AI Coding을 활용하여, 초기 설계부터 Vercel 커스텀 도메인 배포, 카카오링크 API 및 Open Graph 태그 설정까지 **단 하루 만에** 전체 사이클 완수 🎉
- **Tool Utilization & Architecture**:
  - **UI/UX 흐름 구성**: 메인 커버, 인사말, 신랑신부 소개, 예식 정보, 마음 전하실 곳, 위치 안내까지 핵심 섹션들을 스크롤 한 번으로 매끄럽고 끊김 없이 경험할 수 있도록 동선 최적화.
  - **시간 동기화 (D-Day 카운터)**: Date 객체와 setInterval을 활용해 예식장 도착까지 남은 밀리초 단위의 시간을 실시간으로 보여주는 직관적인 카운트다운 컴포넌트 탑재.
  - **Maps Integration (딥링크 구현)**: 웹 내 Google Map 임베드 뿐만 아니라, 모바일에서 가장 사용 빈도가 높은 '네이버 지도' 앱으로 즉시 연결되는 딥링크(Deep-link) 버튼을 구현, 하객들의 체감 편의성 극대화.
  - **Mobile-First Design (Carousel & Accordion)**: 셔틀버스, 주차장 같은 긴 안내 페이지는 좌우 스와이프가 지원되는 **캐러셀(Carousel)** 형태로 묶고, 계좌 번호는 영역을 절약하는 **아코디언(Accordion)** 접이식 UI로 구현해 모바일 환경에서의 가독성 극대화.
  - **Kakao SDK 연동**: 카카오링크 API와 Custom Open Graph(OG) 썸네일을 완벽 연동하여, 청첩장 내부에서 원클릭으로 카카오톡 규격에 맞는 커스텀 메시지를 즉시 공유할 수 있도록 네트워크 트러블슈팅 및 구현 해결.
  - **Firebase Storage 연동**: 예식 당일 하객들의 시선에서 촬영한 생생한 사진을 손쉽게 업로드하고 다함께 볼 수 있도록 **Firebase Storage** 기반 게스트 이미지 리스트업 갤러리 연동 및 보안 룰 최적화.

<p align="left">
  <img src="https://img.shields.io/badge/Google%20Antigravity-4285F4?style=flat-square&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/Kimi-FF6B35?style=flat-square&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Kakao%20API-FFCD00?style=flat-square&logo=kakao&logoColor=black" />
</p>

#### 💻 [삼성전자 PSU Calculator](https://samsungpsu.vercel.app/) ('26.2 1차 Deploy/기능 고도화 작업 중)

> **임직원들을 위한 PSU 가치 시뮬레이션 웹 애플리케이션** (React 19 + TypeScript 기반)

- **주요 기능**: 예상 주가에 따른 PSU 0x ~ 2.0x 지급 배수 자동 계산, 직급별 기준(CL1-2, CL3-4) 모델링 및 KST 기준 캐싱.
- **Tool Utilization & Troubleshooting**:
  - **Vercel Serverless Functions**: 무료 외부 Proxy의 대역폭 한계와 CORS 이슈를 극복하기 위해 자체 API Endpoint를 구축하여 서비스 안정성 확보.
  - **Vercel Edge Caching**: Yahoo Finance API의 잦은 호출로 인한 Rate Limit 문제를 타개하기 위해 12시간 단위 Edge Caching을 적용, 응답 속도 최적화 및 외부 API 의존도 저감.
  - **Bundle Optimization**: 무거운 써드파티 라이브러리(radix, axios, recharts 등) 의존성을 과감히 제거하고 순수 React 기반으로 성능을 최적화하여 쾌적한 오가닉 트래픽 환경 구축 및 구글 Adsense 연동 완료.

<p align="left">
  <img src="https://img.shields.io/badge/Google%20Antigravity-4285F4?style=flat-square&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20AdSense-EA4335?style=flat-square&logo=googleadsense&logoColor=white" />
  <img src="https://img.shields.io/badge/Kimi-FF6B35?style=flat-square&logo=openai&logoColor=white" />
</p>

#### 📱 GRABITY AI (개발 진행 중)

> **"한계를 극복하며 성장을 기록하다"** — AI 분석 기반 피트니스 훈련 로그 및 소셜 네트워킹 모바일 앱 (Flutter 기반)

- **주요 기능**: Offline-first 아키텍처, 7개 언어(SID 기반) 지원, AI 자연어 인식 루틴 생성 모듈, Custom 숫자 및 차트 위젯.
- **Tool Utilization & Troubleshooting**:
  - **Flutter Migration**: 기존 React 기반 프로토타입의 퍼포먼스 제약과 모바일 제스처 한계를 극복하기 위해 Flutter 생태계로 전면 포팅하여 Native 앱 수준의 렌더링 성능 확보.
  - **ReorderableListView & State Management**: 복잡한 드래그 앤 드랍 운동 루틴 UI를 구현하며 발생하는 애니메이션 및 병렬 상태 동기화 이슈를 트러블슈팅하여 매끄러운 UX 제공.
  - **Data Visualization & Optimization**: 커스텀 차트 패키지를 활용해 다양한 주기(1W/1M/3M/All)의 운동 볼륨 및 12주 트렌드 변화 시각화 과정에서 발생한 렌더링 부하 최적화.

<p align="left">
  <img src="https://img.shields.io/badge/Google%20Antigravity-4285F4?style=flat-square&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/App%20Store-0D96F6?style=flat-square&logo=appstore&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20Play-414141?style=flat-square&logo=googleplay&logoColor=white" />
  <img src="https://img.shields.io/badge/Kimi-FF6B35?style=flat-square&logo=openai&logoColor=white" />
</p>

<br/>

[![chnyl's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=chnyl&theme=react-dark)](https://github.com/ashutosh00710/github-readme-activity-graph)
