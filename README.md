# 조성호 (Seongho Cho)

**Physical AI와 로보틱스에 관심을 두고, 시뮬레이션과 실제 하드웨어에서 직접 만들어 보며 공부하고 있습니다.**

## About

광운대학교 정보융합학부(데이터사이언스 전공 트랙)에 재학 중이며, 머신러닝·데이터베이스·영상처리를 공부했습니다.
현재 박재성 교수님 연구실 학부연구생으로 CARLA 시뮬레이터 기반 자율 발렛 주차(AVP) 연구를 하며, 딥러닝에 대해 공부하고 있습니다.
커뮤니케이션 디자인 전문대 과정과 군 복무를 마친 뒤, 논리적 사고에 적성이 있다는 것을 알고 데이터사이언스로 진로를 바꿨습니다.
지금은 인식 결과가 로봇과 차량의 움직임으로 이어지는 과정에 관심을 두고, 작은 프로젝트부터 하나씩 만들어 보고 있습니다.

- **관심 분야**: 컴퓨터비전 · Physical AI · 로보틱스 · 자율주행 · VLA / 모방학습
- **희망 직무**: AI·ML 엔지니어 · Edge AI / MLOps

## Research & Projects

<!-- TODO: 저장소 목록을 받은 뒤 '링크' 열과 각 프로젝트에 저장소 주소를 연결합니다. -->

| 프로젝트 | 구분 | 핵심 키워드 | 링크 |
|---|---|---|---|
| 자율 발렛 주차 (AVP) `진행 중` | 연구실 | CARLA · BEV · Hybrid A\* · Flow Matching | [추가 예정] |
| 협동로봇실습 프로젝트 | 수업 | [추가 예정] | [추가 예정] |
| DofBot 분리수거 Pick & Place `진행 예정` | 수업 (Physical AI실습) | YOLO · SmolVLA · 모방학습 | [추가 예정] |
| 라즈베리파이 자율주행차 | 팀 프로젝트 (4인) | DonkeyCar · YOLO | [추가 예정] |
| 라즈베리파이 표적 추적 | [추가 예정] | 카메라 · 서보모터 제어 | [추가 예정] |
| 휴머노이드 로봇 산업 조사 | 글로벌 IC-PBL | WRC 2026 · 사업화 방안 | [추가 예정] |
| ROBOTIS 오픈소스 기반 학습 `학습 중` | [추가 예정] | AI Worker · CYCLO · VLA · 강화학습 | [추가 예정] |

### Research

**Publication**

- **조성호** (제1저자), 「플로우 매칭 기반 최적 주차 경로 생성 기법」, 대한전기학회 정보제어학술대회(CICS) 학부생 발표부문, 포스터 발표, [2026.11.19]

#### 자율 발렛 주차 (AVP) — 박재성 교수님 연구실 `진행 중`

- **문제**: CARLA 시뮬레이터 환경의 자율 발렛 주차에서, OCP 솔버로 풀던 최적 주차 경로 생성을 학습 기반 모델로 대체하는 방법을 다룹니다. [OCP 솔버를 대체하려는 이유 추가 예정]
- **접근**: 시스템은 CVT 기반 BEV 인식 → HITL(Human-in-the-Loop) 슬롯 선택 → Hybrid A\* 경로 계획 → 동적 장애물 대응으로 구성됩니다. 이 중 경로 생성 부분에서 OCP 솔버를 대체하는 Flow Matching 기반 주차 경로 생성 모델을 연구했습니다.
- **사용 기술**: CARLA, CVT (BEV 인식), Hybrid A\*, Flow Matching
- **결과**: 위 논문 제1저자로 학술대회 포스터 발표 · [결과 추가 예정]

### Projects

#### 협동로봇실습 — 수업 프로젝트

- **문제**: [추가 예정]
- **접근**: [추가 예정]
- **사용 기술**: [추가 예정]
- **결과**: [추가 예정]

#### DofBot 분리수거 Pick & Place — Physical AI실습 `진행 예정`

- **문제**: 분리수거 대상 물체를 인식하고, 로봇팔로 집어 옮기는 Pick & Place 작업을 다룹니다.
- **접근**: YOLO로 객체를 인식하고, SmolVLA를 모방학습으로 파인튜닝해 로봇팔을 제어할 계획입니다.
- **사용 기술**: YOLO, SmolVLA, 모방학습, DofBot (Yahboom), Raspberry Pi 5
- **결과**: [추가 예정]

#### 라즈베리파이 자율주행차 — 팀 프로젝트 (4인)

- **문제**: 라즈베리파이 기반 차량이 차선을 따라 주행하면서 표지판을 인식하도록 만드는 것이 목표였습니다.
- **접근**: DonkeyCar의 LineFollower를 활용한 룰베이스 차선 주행에 YOLO 기반 표지판 인식을 결합했습니다. [본인 역할 추가 예정]
- **사용 기술**: Raspberry Pi, DonkeyCar (LineFollower), YOLO
- **결과**: [결과 추가 예정]

#### 라즈베리파이 표적 추적

- **문제**: 카메라로 표적을 찾아, 장치가 표적을 계속 바라보도록 하는 것이 목표였습니다.
- **접근**: 카메라 영상에서 표적을 인식한 뒤, 서보모터 출력값을 계산해 표적 방향으로 회전시킵니다. [표적 인식 방식 추가 예정]
- **사용 기술**: Raspberry Pi, 카메라, 서보모터 제어
- **결과**: [결과 추가 예정]

### Exploring Next

#### 휴머노이드 로봇 산업 조사 — 글로벌 IC-PBL

- **문제**: 휴머노이드 로봇을 어떻게 사업화할 수 있을지 조사했습니다.
- **접근**: WRC 2026과 연계해 베이징 휴머노이드 로봇 산업 현장을 탐방했습니다. (2026.08)
- **사용 기술**: 산업 조사, 현장 탐방
- **결과**: [결과 추가 예정]

#### ROBOTIS 오픈소스 기반 VLA·모방학습·강화학습 `학습 중 · 진행 예정`

- **문제**: 오픈소스 로봇 플랫폼에서 VLA·모방학습·강화학습을 직접 다뤄 보는 것이 목표입니다.
- **접근**: ROBOTIS 오픈소스(AI Worker, CYCLO)를 공부하고 있으며, 이를 기반으로 프로젝트를 진행할 예정입니다.
- **사용 기술**: ROBOTIS AI Worker, CYCLO, VLA, 모방학습, 강화학습
- **결과**: [결과 추가 예정]

<!-- TODO: 위 프로젝트에 포함되지 않는 저장소는 저장소 목록을 받은 뒤 여기에 정리합니다. -->

## Awards

- **매치업 심화과정 우수상** (실무보고서 · 포스터) — 광운대학교 「로봇산업입문」 수업 · [2025]

## Experience

| 기간 | 내용 |
|---|---|
| [시작 시점 추가 예정] – 현재 | **박재성 교수님 연구실 학부연구생** · CARLA 기반 자율 발렛 주차(AVP) 연구 |
| 2026.08.22 – 08.25 | **글로벌 IC-PBL 비교과 프로그램** · 베이징 휴머노이드 로봇 산업 탐방 (WRC 방문 등) |
| 2025.03.23 | **DeButhon 블록체인 해커톤** 운영진 |
| 2025.01 – 2025.12 | **학과 학생회** 부회장 |
| 2024.09 – 2025.06 | **블록체인 학회 De-Butler** 학회원 및 운영진 |

## Tech Stack

| 분류 | 기술 |
|---|---|
| Language / Framework | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C++ Learning](https://img.shields.io/badge/C%2B%2B-Learning-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![ROS 2 Learning](https://img.shields.io/badge/ROS_2-Learning-22314E?style=flat-square&logo=ros&logoColor=white) |
| AI / Deep Learning | ![Flow Matching](https://img.shields.io/badge/Flow_Matching-5A4FCF?style=flat-square) ![Transformer](https://img.shields.io/badge/Transformer-5A4FCF?style=flat-square) ![BEV Perception (CVT)](https://img.shields.io/badge/BEV_Perception-CVT-5A4FCF?style=flat-square) ![YOLO](https://img.shields.io/badge/YOLO-5A4FCF?style=flat-square) ![VLA](https://img.shields.io/badge/VLA-SmolVLA_%C2%B7_ACT_%C2%B7_%CF%800-5A4FCF?style=flat-square) ![Imitation Learning](https://img.shields.io/badge/Imitation_Learning-5A4FCF?style=flat-square) |
| Embedded / Hardware | ![Raspberry Pi 5](https://img.shields.io/badge/Raspberry_Pi_5-A22846?style=flat-square&logo=raspberrypi&logoColor=white) ![DofBot (Yahboom)](https://img.shields.io/badge/DofBot-Yahboom-333333?style=flat-square) ![Servo Motor Control](https://img.shields.io/badge/Servo_Motor_Control-333333?style=flat-square) |
| Environment / Tools | ![WSL Ubuntu 22.04](https://img.shields.io/badge/WSL-Ubuntu_22.04-E95420?style=flat-square&logo=ubuntu&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square) ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white) |

<sub>`Learning`: 현재 학습 중인 기술입니다.</sub>
