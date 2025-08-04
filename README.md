# 👋 안녕하세요, 임베디드 개발자가 되기 위해 공부하는 문병일입니다.

![Profile Banner](https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=200&text=Welcome%20to%20My%20GitHub&fontSize=40&fontColor=ffffff)


## 🚀 소개
- 🔧 **다양한 MCU 기반 임베디드 시스템 개발 경험**  
  (STM32 F429ZI, F103RB, F411RE 시리즈, Atmega128A, Raspberry Pi, Jetson Nano)  
- 🛠 **하드웨어 제어, 펌웨어, 센서 제어 등의 임베디드 시스템 구축 경험**  
- 🐧 **Linux & Ubuntu 기반 개발경험, 리눅스 커널 구조 학습 중**  
- 🤖 **YOLO, TensorFlow 등 AI 모델을 임베디드 환경과 결합한 프로젝트 경험(RaspberryPi)**  
- 📡 **CAN 통신, 네트워크 연동, 센서 데이터 처리 경험 **  
- 🌱 **멀티 태스킹을 위한 플래그 기반 비동기 시스템, RTOS 기반 멀티 태스킹, 다중 타이머 결합 기반 멀티 태스킹 경험**
- 📖 **연구 논문 기반 문제 해결 경험**  
  - *자동차 외관 손상 탐지*: 논문 기반 객체 검출 방법 학습 후 프로젝트에 적용
  - *스테레오 비전 시스템*: 연구를 참고한 정밀 깊이 추정 및 정합 기법 구현 
  - *PID 제어*: 제어 이론 논문을 기반으로 파라미터 튜닝 및 안정성 최적화 


---

## 🛠 기술 스택
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-FF6F00?style=flat&logo=ai&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=flat&logo=androidstudio&logoColor=white)

---

## 📂 주요 프로젝트

### 1. 🤖 비전 및 객체 인식 , 분류 기반 팔로잉 로봇카  
[🔗 저장소 바로가기](https://github.com/david1597-embedded/aumo_reco_project)  
- **기능**: 카메라 기반 객체 인식 → 손동작으로 실시간 추종 제어  
- **기술 스택**: OpenCV, Python, RPi.GPIO
- **특징**: 비젼을 기반으로한 회전각, 거리 데이터 측정. 사람 객체 인식과 손동작 분류 알고리즘을 결합하여 다양한 로봇카 제어.

---

### 2. 🏢 .SCAN 알고리즘 기반 엘리베이터 제어 시스템  
[🔗 저장소 바로가기](https://github.com/david1597-embedded/elevatorproject)  
- **기능**: **.SCAN 알고리즘**을 이용한 효율적인 엘리베이터 요청 처리  
- **기술 스택**: C, 상태머신, 스테퍼 모터의 실험적 제어, SCAN 알고리즘을 참고하여 만든 엘리베이터 알고리즘  
- **특징**: 3층 건물에서의 요청 기반 엘리베이터 제어 시스템 구축. SCAN 알고리즘을 기반으로 하여 방향 우선 제어. 큐 기반 요청 관리 시스템 구축.

---

### 3. 🚗 CAN 통신 기반 자동차 대시보드  
[🔗 저장소 바로가기](https://github.com/david1597-embedded/can_project)  
- **기능**: CAN 통신을 통해 차량 모터 데이터, 방향 등의 데이터를 수집하고 대시보드로 출력  
- **기술 스택**: C, CAN Protocol, STM32  , ILI9341 TFT LCD , 엔코더 DC모터
- **특징**: 실시간 속도, RPM등의 속도 데이터와 전 후진 , 조향 각 등의 데이터를 송수신. 속도데이터는 TFT LCD에 출력.

---

### 4. 🅿️ 서버 연동 주차장 상태 열람 시스템  
[🔗 저장소 바로가기](https://github.com/david1597-embedded/parkinglot_project)  
- **기능**: 웹서버 연동을 통한 주차 공간 상태 실시간 조회  
- **기술 스택**: C, 네트워크 통신, 데이터베이스(SQL), Flask, Android Studio , Python  
- **특징**: 실시간 주차 현황 업데이트 및 안드로이드 어플리케이션 개발. 안드로이드 어플리케이션과 데이터베이스 서버 연동.
            메인 보드에서 멀티태스킹을 위한 인터럽트와 플래그를 기반으로 만든 멀티 태스킹 시스템.

---

## 🏆 성과 및 활동
![Gold Award](https://img.shields.io/badge/졸업%20프로젝트-금상-FFD700?style=for-the-badge&logo=medal&logoColor=white)
![Silver Award](https://img.shields.io/badge/Intel%20Edge%20AI%20SW%20아카데미%20프로젝트-은상-C0C0C0?style=for-the-badge&logo=intel&logoColor=white)

---

## 🔗 연락처 & 블로그
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:kkhyun3131@gmail.com)
[![Velog](https://img.shields.io/badge/Velog-20C997?style=flat&logo=velog&logoColor=white)](https://velog.io/@david1597/posts)


