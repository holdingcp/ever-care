# ever-care      
   
   
### 아이디어 설명   
![ever_care](https://user-images.githubusercontent.com/88263745/152624372-933b8a6e-3b71-4659-b09d-0a36e2d41897.png)   
반려견의 등과 옷 부분 사이에 웨어러블 디바이스의 형태로 제품을 부착하여 자이로센서, GPS 센서, 가속도 신호 센서 등 각종센서로 수집한 데이터를 블루투스, 데이터 전송 모듈 등을 통하여 자사 클라우드 데이터베이스에 저장 한다. 그 후 사용자의 핸드폰 모바일 앱, 웹에 데이터를 전송하여 반려견의 걸음걸이, 활동량과 같은 트랙킹 결과를 보고 한다. 반려견의 평상시의 걸음걸이와 대비되는 지속적인 이상 징후를 견주가 포착함으로써 큰 수술이 아닌 주의, 재활 , 예방 의학 단계에서 질병의 크기를 줄여 줄 수 있게 알려주는 웨어러블 형태의 디바이스.


### 사용 센서   
![gyro_sensor](https://user-images.githubusercontent.com/88263745/152624756-032b9e1a-b0f2-47e7-a4dd-aae469370d41.png)  
6축 가속도 자이로 센서 (MPU-6050)  
- 3개의 가속도 센서와 2개의 자이로센서. 1개의 온도 센서로 이루어짐.  


![bluetoothsensor](https://user-images.githubusercontent.com/88263745/152624762-2b6aa3a7-f698-41c7-92f2-313834b44f18.png) ![bluetoothsensor1](https://user-images.githubusercontent.com/88263745/152624766-e2fb488f-06fd-4712-a4ff-ddbc697c5495.png)  
블루투스 센서 (HC-06)  
- 휴대폰, 노트북등의 휴대기기를 연결해 정보를 교환 할 수 있도록 하는 근거리 무선 기술 표준.  
- 10m정도의 초 단거리에서 저 전력 무선연결을 위해 사용.


![gps_sensor1](https://user-images.githubusercontent.com/88263745/152624774-4e5f7de9-5519-4528-8993-36a702cbeab4.png) ![gps_sensor2](https://user-images.githubusercontent.com/88263745/152624779-e817837c-da96-43f7-8dc6-486b4b1ad201.png)  
GPS 센서 (NEO-6M)  
- 3개의 위성으로부터 받은 신호를 통해 현재 위치의 위도와 경도, 시간, 속도 등 측정 가능 


![lora_sensor1](https://user-images.githubusercontent.com/88263745/152624788-74bbf1dd-00f4-412e-9cc6-1de54fef2de7.png) ![lora_sensor2](https://user-images.githubusercontent.com/88263745/152624789-bb2e66a8-6230-4984-a70a-4882faca6942.png)  
Lora 센서  
-로라는 보안성과 저전력, 고효율의 장거리 통신이 가능
-비용상의 이점이 크다 (2달러 미만)
***

### 구현
간단하게 시각화가 가능한 processing 언어를 사용하여 프로그래밍 하였고, Arduino와 연동하여 사용하였으며  
센서를 통해 움직임을 감지하는 것까지 구현을 완료하였음.

### 하드웨어 기기 구현  
![hardware](https://user-images.githubusercontent.com/88263745/152625955-032f68ad-3233-4d26-9c94-08b37280abd7.jpg)


### 웨어러블 기기 컨트롤 앱 서비스 이미지  
* 앱 인벤터를 사용하여 구현하였음.


![app1](https://user-images.githubusercontent.com/88263745/152625972-6033c800-1696-4e98-9600-d97f787f517b.jpg) 
![app2](https://user-images.githubusercontent.com/88263745/152625975-05a60015-d0be-400e-abf7-66c9cde0c85a.jpg)


### 제품의 활용  
- 애견의 활동량 및 걸음걸이를 빅데이터 추적 및 분석.
- 애견의 이상징후를 분석하여 초기에 인지함으로써 애견 관련 고비용 시술이나 수술 확률을 낮춤.
- 추적한 데이터를 분석하여 견주에게 제공 -> 견주가 스스로 애견의 운동량 조절 , 영양제 섭취, 생활 속에서 더 DETAIL한  관리가 가능하도록함.


### 향후 계획  
- 시장 조사를 통해 고객의 NEEDS 추적 -> 사업화 가능성 지속 분석.
- 하드웨어 소형화 및 고도화.
- PLATFORM , DATABASE, Data Analaysis등 시스템 구축 및 고도화  
- 초기 데이터 및 데이터 마이닝 시스템화
