장애물, 차량, 차선 감지

장애물 및 차량 ->yolov5-master
차선 감지 -> openCV

### version 1.0
약 6천장의 차량과 장애물 데이터를 사용하여 학습을 진행함.

### version 1.1
기존 데이터셋은 pretrained model 보다 더 낮은 정확도를 보이기 때문에 새로운 차량 데이터 16185장과 보행자 데이터 2601장을 추가하여 학습함
총 데이터셋 21737(train 17322/val 4415)
보행자 데이터셋 같은 경우에는 이미지 수는 작으나 instance는 1만정도 이므로 학습에 충분하다고 생각됨.

### version 1.2
전의 데이터 셋의 결과가 좋지 않아 도로주행영상 데이터셋을 사용하여 새로 학습 (train set: 167,621 val set: 10,371) 
보행자, 신호등, 도로표지판, 로드마크 등 새로운 클래스 추가

> ### **dataset & weigth file link**
> ### 
> ### https://aihub.or.kr/aihub-data/autonomous/about

### version 2.0
차선 인식 추가

### version 2.1
차간 거리 인식 추가
차간 거리별 시나리오 일부 추가

### version 2.2
거리 인식 초점 수정

### version 2.3
차선 이탈 시나리오 추가

### version 2.4
신호위반 시나리오 추가
기존 시나리오 성능 향상

### version 3.0
웹 추가
