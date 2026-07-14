<div align="center">

# Hi, I'm Kyoungmin Kwon 👋

### Frontend Engineer building reliable interfaces for real-time, high-volume data

> **“굳이 이 방식이어야 할까?”에서 시작해, 실제 운용과 다음 개발자까지 확인합니다.**

React와 TypeScript를 중심으로 산업용 분석 도구를 개발합니다.  
화면에 보이는 결과뿐 아니라 성능 병목의 원인, 시스템의 운영 조건, 코드를 이어받을 사람의 경험까지 살핍니다.

[![Portfolio](https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio.lanos0609.workers.dev/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lanos0609@gmail.com)
[![NPM](https://img.shields.io/badge/NPM-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/~kwon-kyoungmin)

</div>

---

## About Me

- **표면적인 설명에서 멈추지 않습니다.** 문서만으로 원인을 찾기 어려우면 프로파일러와 라이브러리 소스까지 따라갑니다.
- **모델과 시스템의 가치는 운용에서 확인합니다.** 학습 지표뿐 아니라 실시간 지연, 시간 정합성, 실패 경계까지 검증합니다.
- **제가 만든 것 앞에서 누군가 헤매지 않게 합니다.** 재사용 가능한 구조, 테스트, 문서를 제품의 일부로 생각합니다.
- **혼자 푸는 것보다 함께 정확히 푸는 법을 배우고 있습니다.** 서로의 빈 영역을 채울 때 더 나은 설계가 나온다고 믿습니다.

---

## Selected Work

### High-volume Log Analysis UI

React와 Electron 기반 산업용 로그 분석 도구에서 장시간 실행 시 발생하던 메모리 증가와 렌더링 병목을 추적했습니다.

- 초당 **80,000건**의 스트리밍 로그를 UI 멈춤 없이 처리
- 렌더링 시간 **1.04s → 450ms**, 약 **2.3배 개선**
- 메모리 사용량 **3.3GB → 2.0GB**, 약 **30% 감소**
- Heap snapshot과 라이브러리 소스 분석으로 내부 캐싱 문제를 추적

### Real-time AI Visualization with CARLA

학습 지표는 정상인데 시뮬레이션 화면에서는 예측 궤적이 어긋나 보이는 문제를 모델 정확도가 아닌 **추론 지연과 시뮬레이터 Tick의 시간 정합성** 관점에서 분석하고 있습니다.

- 비동기 추론 시간을 고려한 궤적 offset 보정
- 동기·비동기 추론 파이프라인 분리
- Point-wise 검증 모듈과 실시간 다중 궤적 시각화 구축

> 모델의 가치는 학습 결과만이 아니라, 실제 환경에서 어떻게 동작하는지로 결정된다고 생각합니다.

### [Mini ATS Matching System](https://github.com/km-kwon/trading-system)

자동매매나 수익률 예측이 아니라, 거래 시스템이 **정확성과 복구 가능성**을 어떻게 유지하는지 이해하기 위해 C++20 기반 매매체결 시스템을 구현했습니다.

- 가격-시간 우선 Order Book과 LIMIT / MARKET / IOC / FOK 주문 처리
- Deterministic replay, TCP gateway, UDP market data publisher 구현
- GoogleTest 기반 **14개 test suite, 92개 unit test** 통과
- 고정 Release benchmark에서 **약 792K commands/sec** 기록

---

## Open Source

업무 중 발견한 반복적인 문제를 프로젝트 안의 임시 코드로 남기지 않고, 다른 개발자도 설치해 사용할 수 있는 패키지로 정리합니다.

| Package | What it solves | Links |
| :--- | :--- | :--- |
| **circular-queue-react** | 스트리밍 데이터를 안정적으로 유지하는 O(1) 원형 큐와 React 연동 | [GitHub](https://github.com/km-kwon/circular-queue-react) · [![npm](https://img.shields.io/npm/v/circular-queue-react?style=flat-square&color=CB3837)](https://www.npmjs.com/package/circular-queue-react) |
| **broadcast-event-system** | 컴포넌트 결합도를 낮추는 zero-dependency Pub/Sub 이벤트 시스템 | [GitHub](https://github.com/km-kwon/broadcast-event-system) · [![npm](https://img.shields.io/npm/v/broadcast-event-system?style=flat-square&color=CB3837)](https://www.npmjs.com/package/broadcast-event-system) |

> `node_modules` 안에서 제가 작성한 코드를 처음 발견했을 때, 재사용 가능한 소프트웨어를 만든다는 일이 오래 기억에 남았습니다.

---

## Tech I Work With

**Core**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433E38?style=flat-square&logo=react&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![ECharts](https://img.shields.io/badge/ECharts-AA344D?style=flat-square&logo=apacheecharts&logoColor=white)

**Also experienced with**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![ZeroMQ](https://img.shields.io/badge/ZeroMQ-DF0000?style=flat-square&logo=zeromq&logoColor=white)

---

<div align="center">

**I ask why, verify in operation, and leave a path for the next developer.**

</div>
