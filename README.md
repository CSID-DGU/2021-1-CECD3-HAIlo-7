# 2021-1-CECD3-HAIlo-7

### FFmpeg과 YOLO를 이용한 객체 탐지 자동화 솔루션
#### 객체 탐지 영역에서의 자율주행 학습 이미지 데이터 셋 자동 수집 프로그램 🚘

## 팀 HAIlo 
2017112106 신소희   
2017112094 이은영   
2018113338 조성운   
2017112100 한유진 

## 주제 선정 배경

|AI 프로젝트에 소요되는 시간 비율|한국형 자율주행 데이터셋의 부족 현상|
|:----|:----|
|![image](https://user-images.githubusercontent.com/48276490/122639055-b0389400-d132-11eb-9e02-a75ec9d4ed8a.png)|![image](https://user-images.githubusercontent.com/48276490/122639024-9303c580-d132-11eb-8654-2d69e4c7d4c0.png)|
|대량의 학습 데이터를 수집하는 시간이 AI 개발 일정의 대부분을 차지한다.|외국과 대비해 한국은 원천데이터 확보와 데이터 라벨링에 대한 체계가 잡혀있지 않아 국내 도로 상황에 맞춰진 학습 데이터 확보가 절실하다.  |
<br> 

## 개발 목적
<img src="https://user-images.githubusercontent.com/48276490/122639889-7322d080-d137-11eb-90d1-a7c01f7e7299.png" width="80%" height="100%">

사용자(개발자)들이 쉽고 편리하게 접근하여 학습 데이터 셋을 얻을 수 있도록 <br>
자율 주행 학습 데이터 자동 어노테이션 서비스를 제공하는 웹 사이트를 구축하는 것이 목적
<br><br>

## 시스템 구성도
![image](https://user-images.githubusercontent.com/48276490/122640221-3eb01400-d139-11eb-9ee9-8a758326130e.png)
<br>

## 주요 기능
1. 수집하고자 하는 객체 선택 가능
2. 객체를 탐지할 대상 영상 데이터(이미지 및 동영상) 입력 가능
3. 수집된 이미지와 메타 데이터 제공 (bounding box annotation 정보)
4. Image Augmentation 기능 선택 가능
<br><br>

## 제공 객체 클래스
![image](https://user-images.githubusercontent.com/48276490/122640272-a5cdc880-d139-11eb-9652-6374a309dc2b.png)
<br><br>

## 현재 진행 상황
* 제공할 객체 클래스에 대한 이미지 수집 및 라벨링 진행 중 <br>

<img src="https://github.com/CSID-DGU/2021-1-CECD3-HAIlo-7/blob/main/images/readme_image/%EC%A7%84%ED%96%89%EC%82%AC%ED%95%AD.PNG?raw=true" width="80%" height="100%">
<br><br>

## 개발 환경
<img src="https://img.shields.io/badge/html-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white">
<img src="https://img.shields.io/badge/aws-232F3E?style=for-the-badge&logo=aws&logoColor=white">
<br><br>


## 프로토타입
![HAIlo(prototype)](https://user-images.githubusercontent.com/48276490/122640459-b6cb0980-d13a-11eb-8aa4-1a58df6d04c8.gif)
<br><br>

## 향후 계획
1. 남은 클래스에 해당하는 객체 이미지 수집 및 라벨링 완료
2. BDD 100K, AIhub에서 제공하는 동영상 DB 구축
3. 웹 페이지 구현 완료

