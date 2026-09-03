<div align="center">

# 김중우

### Robotics · Computer Vision · Embedded AI

로보틱스와 컴퓨터 비전에 관심이 있으며,  
관련 분야의 기술을 연구하고 공부하면서 실제 시스템으로 구현하는 과정을 이어가고 있습니다.

<br>

<a href="https://github.com/Kimjw2024">
  <img src="https://img.shields.io/badge/GitHub-Kimjw2024-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>
<img src="https://img.shields.io/badge/Robotics-1976D2?style=for-the-badge&logo=robotframework&logoColor=white" alt="Robotics">
<img src="https://img.shields.io/badge/Computer%20Vision-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="Computer Vision">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">

</div>

---

## About Me

저는 카메라와 AI를 실제 로봇·임베디드 시스템에 연결하는 일에 관심이 있습니다.  
컴퓨터 비전 기반의 인식과 3D 위치추정, 센서 데이터 처리, 임베디드 통신과 제어를 공부하며 작은 기능을 실제 동작하는 시스템으로 확장하는 연구를 진행하고 있습니다.

| 관심 분야 | 학습·연구 내용 |
| --- | --- |
| Robotics | 로봇 시스템 구성, 좌표계, 기구학, pan-tilt 및 actuator 제어 |
| Computer Vision | 객체 검출, 분류, stereo vision, camera calibration, depth estimation |
| 3D Perception | 다중 카메라, triangulation, metric depth, 3D localization |
| Embedded AI | Raspberry Pi, Arduino, 실시간 영상 전송과 장치 연동 |
| Engineering | 실험 설계, 결과 분석, 재현 가능한 문서화 |

---

## Featured Project

### AEGIS

#### AI 기반 공항 Bird-Strike 예방·대응 시스템

AEGIS는 공항 주변 조류를 인식하고 위치와 움직임을 분석해 위험 상황에 대응하는 것을 목표로 하는 공동 프로젝트입니다. 2대의 Raspberry Pi와 4대 카메라에서 영상을 수집하고, multi-baseline stereo vision으로 조류의 3D 위치를 추정한 뒤 tracking, 위험도 판단, dual pan-tilt response까지 연결했습니다.

<p align="center">
  <img src="https://raw.githubusercontent.com/tigerjueun/2026ESWContest_free_AEGIS/main/assets/system/system_overview.png" alt="AEGIS integrated prototype" width="820">
</p>

#### System Highlights

- 2 Raspberry Pi · 4-camera distributed vision system
- 6 stereo pairs 기반 multi-baseline 3D localization
- YOLO 기반 bird detection과 ResNet-18 조류군 분류
- Kalman filter, LPF, velocity estimation, track hold
- AI Decision Console 기반 species·XYZ·motion·risk 정보 표시
- 3D target을 이용한 dual pan-tilt turret response
- Raspberry Pi · Windows Fusion PC · Arduino 간 통신 및 시스템 통합

#### Selected Results

| Model / System | Result |
| --- | ---: |
| Custom YOLOv8s | Offline mAP@0.5 **97.5%** |
| Custom YOLOv8s | Precision / Recall **96.4% / 93.5%** |
| ResNet-18 | Test Accuracy **94.76%** |
| Camera system | **4 cameras / 6 stereo pairs** |

> 위 AI 수치는 held-out offline test 기준이며, 실시간 현장 성능과는 구분하여 기록했습니다.

#### Links

<a href="https://github.com/Kimjw2024/2026ESWContest_free_AEGIS">
  <img src="https://img.shields.io/badge/My%20AEGIS%20Portfolio%20Repository-6A5ACD?style=flat-square&logo=github&logoColor=white" alt="My AEGIS portfolio repository">
</a>
<a href="https://github.com/tigerjueun/2026ESWContest_free_AEGIS">
  <img src="https://img.shields.io/badge/Original%20Team%20Repository-555555?style=flat-square&logo=github&logoColor=white" alt="Original AEGIS team repository">
</a>

---

## Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,pytorch,opencv,arduino,raspberrypi,git,github,vscode&perline=9" alt="Tech stack">
</div>

### Core Technologies

Python · C++ · OpenCV · PyTorch · YOLO · ResNet-18 · stereo vision · depth estimation

### System Technologies

Raspberry Pi · Arduino · ZMQ · TCP/IP · Serial communication · Windows · VS Code

### Methods

Object detection · Image classification · Camera calibration · Triangulation · Metric depth · Kalman filtering · Coordinate transforms

---

## Research & Engineering Approach

1. 문제를 perception, localization, tracking, decision, control 단계로 나눕니다.
2. 해상도, 좌표계, 통신 포트와 같은 데이터 계약을 먼저 확인합니다.
3. calibration과 실험 결과를 재현 가능한 형태로 남깁니다.
4. 소프트웨어 검증과 실제 하드웨어 실행을 구분합니다.
5. 구현 결과와 추가 연구가 필요한 가설을 문서에서 명확히 구분합니다.

---

## Portfolio Notes

- 이 페이지는 공개 가능한 연구 관심 분야와 AEGIS 프로젝트를 중심으로 구성했습니다.
- AEGIS는 공동 프로젝트이며, 개인 포트폴리오 저장소와 원본 팀 저장소를 함께 연결했습니다.
- 프로젝트 상세 문서, 실행 구조, calibration, AI pipeline과 발표자료 기반 시각 자료는 AEGIS 저장소에서 확인할 수 있습니다.
- 원본 대용량 데이터와 개인 환경 설정은 저장소에 포함하지 않습니다.

<br>

<div align="center">

### Learn deeply. Build carefully. Measure honestly.

<br>

<sub>Last updated: 2026-09-03 · GitHub @Kimjw2024</sub>

</div>