# 클라우드 기반 IoT 도난 방지 모니터링 서비스

**IoT와 클라우드 기술을 활용한 실시간 도난 감지 및 시각화 스마트 알림 시스템**

---

## 📌 프로젝트 개요

이 프로젝트는 2024 ICT 스마트 디바이스톤에서 개발되었으며,  
여행 중 발생할 수 있는 가방 도난 상황을 실시간으로 감지하고 클라우드 기반 웹 대시보드로 사용자에게 알림을 전송하는 시스템입니다.

- **수행 시점**: 2024 ICT 스마트 디바이스톤  
- **팀원 수**: 3명  
- **목표**: 여행 가방 도난 상황을 실시간 감지하고, 위치 기반 경고를 Google 로드뷰로 시각화

---

## 🛠️ 주요 기능

- 센서 및 마이크로컨트롤러를 통한 실시간 도난 감지  
- 클라우드 기반 웹 서비스로 알림 데이터 전송  
- Google Street View API 연동을 통한 위치 시각화  
- 사용자 친화적인 프론트엔드 UI로 실시간 모니터링 제공  
- Netlify를 통한 배포, HTML/CSS/JS 기반의 모듈 구조

---

## 🧠 사용 기술

- JavaScript (프론트엔드 로직)  
- HTML5 / CSS3 (웹 UI 및 디자인)  
- Google Maps & Street View API  
- Netlify (클라우드 배포 플랫폼)  
- IoT 디바이스 (센서 + BLE 또는 Wi-Fi 모듈)

---

## 📁 파일 구조 및 설명

| 파일 / 폴더            | 설명 |
|------------------------|------|
| `index.html`           | 도난 발생 및 지도 출력이 포함된 메인 인터페이스 |
| `script_modified.js`   | 도난 감지 이벤트 처리, Google API 연동, 알림 표시 |
| `styles_modified.css`  | 사용자 인터페이스 스타일 및 디자인 |
| `pxfuel.jpg`           | 배경 이미지 또는 시각적 자료 |
| `functions/`           | Netlify Functions (서버리스 백엔드) |
| `netlify.toml`         | Netlify 배포 설정 파일 |
| `.gitattributes`       | Git 속성 관리용 파일 (줄바꿈 등)

---

## 🎥 영상

- [시연 영상 1](https://youtube.com/shorts/K703nKvYJQI?feature=share)
- [시연 영상 2](https://youtube.com/shorts/cPOWDACozco?feature=share)
- [PCB 영상](https://youtu.be/zFs6c_TpFcU)

---

### 🖼️ 이미지 자료

#### ✅ PCB 이미지

- ![이미지 1](https://github.com/Kim-geun-woo/Real-Time-IoT-Based-Theft-Monitoring-Platform-Project/raw/main/images/image12.jpeg)  
- ![이미지 2](https://github.com/Kim-geun-woo/Real-Time-IoT-Based-Theft-Monitoring-Platform-Project/raw/main/images/image13.png)

#### ✅ 클라우드 / 웹 서비스 UI

- ![Cloud UI](https://github.com/Kim-geun-woo/Real-Time-IoT-Based-Theft-Monitoring-Platform-Project/raw/main/images/image15.png)
- ![Google Street View Integration](https://github.com/Kim-geun-woo/Real-Time-IoT-Based-Theft-Monitoring-Platform-Project/raw/main/images/image19.jpeg)

#### ✅ 앱 서비스 & 멀티 디바이스 지원

- ![App UI 1](https://github.com/Kim-geun-woo/Real-Time-IoT-Based-Theft-Monitoring-Platform-Project/raw/main/images/image16.jpeg)  
- ![App UI 2](https://github.com/Kim-geun-woo/Real-Time-IoT-Based-Theft-Monitoring-Platform-Project/raw/main/images/image17.png)  
- ![Multi Device Support](https://github.com/Kim-geun-woo/Real-Time-IoT-Based-Theft-Monitoring-Platform-Project/blob/main/images/image20.jpeg)

---

## 📎 관련 자료

- 📄 [최종 발표 자료 PDF](https://github.com/Kim-geun-woo/Real-Time-IoT-Based-Theft-Monitoring-Platform-Project/blob/main/docs/2024%20ICT%20%EC%8A%A4%EB%A7%88%ED%8A%B8%20%EB%94%94%EB%B0%94%EC%9D%B4%EC%8A%A4%ED%86%A4%20%EB%B0%9C%ED%91%9C%EC%9E%90%EB%A3%8C%20%EC%B5%9C%EC%A2%85.pdf)

---

## 🧠 사회적 가치 및 차별성

-  여행 중 가방 도난에 대한 실시간 대응 가능성 제공  
-  실제 위치 기반 Google Street View 시각화 제공  
-  경량화된 시스템으로 저사양 디바이스에도 적용 가능  
-  범용적인 기술로 다양한 환경에 손쉽게 적용 가능

