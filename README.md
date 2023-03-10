## 소상공인을 위한 챗봇
#### 기간: 2021.11.27 ~ 2021.12.11

#### 프로젝트 설명: 
- 디지털 장벽 혹은 다양한 이유로 챗봇을 도입하지 못하는 카페 소상공인을 위해 AI Hub데이터를 바탕으로 챗봇 서비스 제작

#### 담당 역할: 
- 트렌스포머를 활용한 모델 개발
- 한국어 대화 데이터 전처리
- Transformer 기반 모델 개발


#### 상세 과정: 
##### 1. AI Hub의 한국어 대화 데이터셋 중 카페업에 관한 내용 선정 및 챗봇에 학습할 수 있도록 전처리 진행
   <img src="https://user-images.githubusercontent.com/93495435/216887134-7ae2ad10-b544-4b10-b24f-c03230793e7d.png" width="500" height="250"/>

##### 2. Transformer 기반으로 챗봇 학습
   <img src="https://user-images.githubusercontent.com/93495435/216888519-f02c302a-7d64-4369-9204-d7198eedbe8a.png" width="500" height="250"/>

##### 3. 모델을 AWS EC2와 카카오 비즈니스 기능을 이용하여 배포
   <img src="https://user-images.githubusercontent.com/93495435/216887202-4cdf1a0e-921c-4d02-97cd-b91f592ee857.png" width="500" height="250"/>

#### 프로젝트 개선사항:
##### 1. 닫힌 대화 챗봇을 구성하려면 S-Bert활용해 구현

##### 2. 더 정확한 모델링을 위해서는 트렌스포머 파라미터 조정
   <img src="https://user-images.githubusercontent.com/93495435/216887276-ecd83f5a-1e7e-4197-970d-5099a7f59fe6.png" width="500" height="250"/>

##### 3. 모델 학습 방법 변경(Transformer → Bert)
   <img src="https://user-images.githubusercontent.com/93495435/216887286-6ebecabb-1232-40d6-ba35-fbb4563ac588.png" width="500" height="250"/>

##### 4. 데이터 전처리 방식 변경
  <img src="https://user-images.githubusercontent.com/93495435/216887293-9f6bd5be-e104-49f3-89b7-598cb2079877.png" width="500" height="250"/>
