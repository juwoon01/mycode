# Machine Learning-based Cavities Diagnosis System
## 개요 
- 보건의료빅데이터개방시스템의 2019년도 다빈도질병 통계를 보면, 치아와 관련된 질환의 빈도가 다른 질환에 비해 높다는 것을 알 수 있다. 
사람의 치아는 영구치 이후로는 더 이상 재생되지 않는다. 따라서 우리는 건강한 치아를 위해서는 주기적이고 지속적인 치아 상태의 모니터링이 매우 중요하다. 
하지만 한 논문에 따르면 우리나라 국민의 87%가 구강 질환을 경험한 적이 있으나, 정기적으로 병원을 방문하여 관리하는 경우는 소수에 불과하다고 한다. 
실제로 치아가 크게 아프지 않은 이상 주기적으로 병원을 방문하기는 시간적으로도 제정적으로도 힘들다.
이에 ‘우리가 매일 사용하는 칫솔로 치아 상태를 모니터링 할 수 있으면 좋겠다.’는 생각을 하게 되었고, 이에 대한 해결 방안으로 스마트 칫솔이 있지 않을까? 라고 생각하여 이에대해 조사를 해보.
그런데 시중에 이미 나와있는 스마트 칫솔들은 사용자의 칫솔질 방법에 대한 모니터링 과 개선 기능에 중점을 두고 치아 상태에 대한 모니터링 기능은 없었다. 
그래서 “스마트 칫솔이나 구강 카메라에 AI 진단기능을 추가한다면 전문가 수준의 치아 상태 모니터링을 일상생활속에서 주기적으로 받을수 있겠다” 라고 생각하였고 이에 Machine Learning을 이용한 치아진단 시스템 연구를 수행하게 되었다.

## 개발 환경
- 주피터 노트북, 라즈비안, 텐서플로, 케라스, 라즈베리파이, 파이썬
- CNN(Convolution Neural Network)
### CNN을 선택한 이유
- 이미지에서 직접 특징 추출 가능
이미지의 인식을 위한 패턴을 찾는데 유용
이미지 classification에서 가장 널리 사용되는neural network
(자율 주행 차량, 얼굴 인식 어플리케이션 등)

## 개발을 위한 학습
- Python 학습(파이썬 기초 강의), 라즈베리파이 학습(모두의 라즈베라파이), 텐서플로우와 케라스(부스트코스 텐서츨로우로 시작하는 딥러닝 기초)

## 결과
- Machine Learning-based Cavities Diagnosis System 에 보이는 것처럼 87%의 accuracy를 보임
AI의 예측 정확도는 상용화에는 부족한 수치입니다. 하지만 데이터의 수가 적었다는것을 고려하면 낮지 않다고 생각함.
만약 외부 기관의 협조등을 통해 많은 데이터를 수집한다면 더 높은 정확도를 가지는 AI로 발전할 가능성이 있다고 생각함.
충분한 이미지 데이터의 수집이 가능하게 된다면 치아뿐만 아니라 피부병이나 탈모, 안구질병과 같이 눈으로 증상 확인이 가능한 질환에 대한 전문가 수준의 자가 진단 시스템 구축이 가능할 것
### 논문
- 논문을 작성하여 국제 정보 네트워킹 학회 ICOIN에 등재 
