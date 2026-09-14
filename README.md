# 버니어 센서 표시기 (Vernier Go Direct Web)

버니어 Go Direct 센서를 **USB(WebHID)** 또는 **블루투스(Web Bluetooth)** 로 브라우저에서 바로 읽어 값을 표시하는 웹앱입니다. 설치가 필요 없습니다.
**2030 꼬마과학자 교실** 프로그램에서 운영하며, [ARGO](https://argo-lyart.vercel.app/)(AI 과학 논증활동 도우미)와 함께 씁니다.

- 크롬 계열 브라우저(Chrome·Edge·**웨일**)에서 **https 주소**로 열어야 동작합니다.
- 센서마다 큰 실시간 값 + 미니 그래프, 스냅샷/자동 기록, CSV 저장·복사.
- 자동 기록: **간격**(0.5초~)과 **측정 시간**(30초/1분/2분/5분/직접 입력/무제한)을 정하면 시간이 다 됐을 때 저절로 멈춥니다.
- 그래프: 막대/꺾은선, 세로축 여러 값, **값 표시(자동·모두·숨김)**, **크기(보통·크게·전체 화면)**, **이미지(PNG) 저장**.
- 최대 4개 센서 동시 연결(전원 공급형 USB 허브 권장).

## 체험 모드
센서가 없을 때 주소 뒤에 `?demo`를 붙이면(예: `index.html?demo`) 가짜 온도·조도 센서로 화면을 시험해 볼 수 있습니다.

## 파일
- `index.html` — 앱 전체(단일 파일)
- `godirect.min.umd.js` — 버니어 오픈소스 라이브러리(내장)
- `brand/kids-scientist-logo.png` — 2030 꼬마과학자 교실 로고

Go Direct sensor library © Vernier Software (BSD-3-Clause).
