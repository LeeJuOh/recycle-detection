# 우리의 품애 (Android)

## 프로젝트 개요

---

- 우리의 품애(愛)는 내가 버린 폐기물의 재활용을 통해 우리들의 품으로 돌아온다는 의미입니다.
- 캡스톤 과목으로 진행한 딥러닝 기반 생활폐기물 인식 모바일 서비스입니다.
- 폐기물에 따라 복잡하고 어려운 배출방법을 해소하고자 이미지 객체 인식 기술과 음성인식 기능을 이용하여 사용자들에게 손쉽게 배출방법을 소개하고자 하였습니다.
- Yolov3 모델의 경우 총 58가지의 폐기물에 대한 분류가 가능하며 객체인식 모델 정확성 평가의 경우 TOP-1 정확도 88.24%, TOP-5 정확도 90.63%를 보여주었습니다.
- 대형폐기물의 경우 길이에 따라 세부 품목이 나뉘어져 복잡한 과정을 거치고 있어 사진을 통해 품목뿐만 아닌 세부 분류 까지 알려 주고 그에 따른 수수료를 알려준다면 문제점이 해결될것같아 해당 부분을 OpenCV를 이용하여 구현하였습니다.
- 길이 측정 오차는 해당 품목의 길이를 기준으로 ± 10% 정도입니다.
- `사용자 요구사항 정의서` `유스케이스 명세서` `클래스 설계서` `시퀀스 다이어그램` `사용자 인터페이스 설계서` `아키텍처 설계서` 등을 팀원들과 함께 작성해보며 완성도 있는 프로젝트를 만들고자 노력하였습니다.

## 프로젝트 사용 기술 및 라이브러리

---

### ✔ Languauge

- Java, Python

### ✔ Server

- Django

### ✔ Client

- Android

### ✔ 협업

- GitHub

### ✔ Deep-Learning

- Yolov3 (Tensorflow)

### ✔ Data Base

- MySQL

### ✔ Library

- OpenCV
- Retrofit2

## 주요 기능

---

- 객체인식 기술을 이용하여 폐기물 품목을 확인할 수 있습니다.
- 음성 또는 텍스트로 폐기물의 배출 요령을 검색할 수 있습니다.
- OpenCV의 마커를 이용하여 대형 폐기물 길이 측정이 가능합니다.
- 대형 폐기물 나눔 커뮤니티를 이용할 수 있습니다.
- 사용자의 지역에 따른 폐기물 배출 관련 정보를 확인할 수 있습니다.
- 객체인식 기술을 이용하여 폐기물의 분리상태에 따라 포인트를 제공합니다.

## 나의 역할

---

- Django api server 개발
- 딥러닝 모델 구현을 위한 데이터 수집 및 정제
- 딥러닝 학습을 통한 image detection(yolo3 기반) 모델 구현
- Open CV 기반 마커를 통한 길이 측정
- DB 설계

[프로젝트 소개](https://foamy-kookaburra-ef9.notion.site/6908b2c2b54747c494d6f2a90c037223)
