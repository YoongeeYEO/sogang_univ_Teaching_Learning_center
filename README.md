# 서강대학교 교수학습센터
* 팀원 : 서강대학교 정보통신대학원 데이터사이언스/인공지능전공 66기 정성실, 이근호, 여윤기
* 활동기간 : 22. 9월 ~ 11월 (약 2달)
* 주제 - YOLOv7 모델을 기반으로 한 주행환경 객체 탐지 / Transformer 기반의 Question & Answer 일상 대화 챗봇 모델
* 주차별 프로젝트 내용(세부 내용은 업로드한 코딩 파일과 주차별 활동보고서 참고)

  - 1주차 : Object Detection 모델 중 빠른 추론 속도에 비해 높은 정확도를 갖는 YOLOv7 모델 논문을 읽고 논문 요약내용을 각자 발표하며 기본적인 개념, 모델 구조, 성능을 분석하였음.
  - 2주차 : 1주차 스터디 학습내용을 바탕으로 Github에 공개된 pre-trained YOLOv7 모델을 인퍼런스 후, 가수 아이유 님의 사진을 포함한 여러가지 테스트 데이터셋 샘플을 활용하여 실제로 논문에서 언급된 것 처럼 Object Detection에서 빠른 추론속도와 높은 정확도를 보이는지 확인하였음.
  - 3주차 : YOLOv7 모델은 빠른 속도 대비 높은 정확도를 나타내는 모델 특성상, 실시간 객체탐지 분야에서 많이 사용되며, 실제 주행환경에서 실시간으로 차량 등의 객체를 탐지할 수 있는 모델을 학습시키기 위해 주행환경 교통수단 데이터셋을 수집하였음.
  - 4주차 : 수집한 데이터셋으로 YOLOv7 모델 학습 진행. 사전 학습된 Pre-trained weight를 사용하지 않고 모델 학습을 통해 weight값을 저장한 모델과, pre-trained된 weight를 사용하여 전이학습을 시킨 모델으로 구분하여 2가지 모델을 학습
  - 5주차 : 테스트 데이터셋 수집 후, 학습시킨 YOLOv7 모델의 결과를 Confusion Matrix를 통해 비교함.
  - 6주차 : 1~5주차까지 학습한 YOLOv7 모델 기반의 주행환경 객체탐지 스터디 내용을 마무리하였고, 남은 학습기간동안 새롭게 공부할 자연어 분야의 여러 가지 모델들에 대해 토의하여 “Transformer – Attention is all you need” 논문으로 학습주제를 선정함.
  - 7주차 : 자연어 처리 모델을 학습하기 위해 관련 선행연구인 “Transformer – Attention is all you need” 논문을 읽고 논문의 핵심 내용을 발표하고 Transformer 모델 이전 자연어 분야에서 많이 사용된 RNN 모델의 동작 원리에 대해 학습함.
  - 8주차 : “Transformer – Attention is all you need” 논문에서 제시한 모델구조를 참고하여 파트별로 코딩을 통해 모델을 직접 구현하며 Transformer 모델의 동작 원리를 학습함.
  - 9주차 : 구현한 Transformer 모델로, Question & Answer 구조로 된 일상 대화 데이터셋을 학습시켜 챗봇 모델로 만든 후 결과를 확인함.
