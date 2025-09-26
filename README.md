# project2


## 1. 댓글 감정 모델 개발  


유튜브 댓글 데이터를 수집하여 감정을 분류하는 모델을 개발한 프로젝트입니다.
단순히 긍/부정 분류를 넘어, 다양한 감정(기쁨, 기대, 애정, 슬픔, 분노, 공포)을 분류하여 더 정교한 감정 분석을 목표로 하였습니다

<br>

## 2. 프로젝트 개요

최근 온라인 플랫폼, 특히 유튜브와 같은 영상 기반 플랫폼에서 사용자 댓글은 중요한 소통 수단이자 여론을 반영하는 지표로 활용되고 있습니다. 그러나 기존 감성 분석 모델은 댓글의 복합적인 의미를 단순히 '긍정' 또는 '부정'으로만 분류하는 한계가 있었습니다. 
이러한 한계를 해결하기 위해, 본 프로젝트에서는 유튜브 댓글을 핵심 데이터로 활용하였고, 제품(편의점 PB상품), 정책(고교학점제), 기술(AI) 3개 분야의 영상 댓글 데이터를 수집하여, 다양한 주제에서 나타나는 대중의 의견을 분석하였습니다.  
프로젝트의 최종 목표는 FORA(Future-Oriented Relational Affect model)라는 새로운 감성 분석 모델을 개발하고 그 실효성을 검증하는 것이었습니다. FORA 모델은 댓글에 담긴 기대감을 통해 미래 가치를 예측하고, 애정과 같은 감정을 통해 사용자와의 관계성을 측정함으로써, 비즈니스와 정책 수립에 실질적인 도움을 줄 수 있는 실행 가능한 인사이트를 도출하는 것을 목표로 하였습니다.

<br>

[댓글 레이블링 지침](https://docs.google.com/spreadsheets/d/1xlZrJ23rKn06P2ixTw3bmeqQuYafdGcx/edit?usp=drive_link&ouid=116413280130938266406&rtpof=true&sd=true) <br>

[추가학습 데이터 300](https://drive.google.com/drive/folders/1DNIRDjtO6cUR180ovZMjauP22MMiu50H) <br>

[다른 조원들 설문 조사 결과](https://docs.google.com/spreadsheets/d/1zeiw7QfgHnu56ry7TomvT-1BYlWXpuuHFBVjeuvrCuc/edit?usp=drive_link) <br>

[Ground Truth](https://drive.google.com/file/d/16maHwAYzigGM_sB6r2KHDJNLeRiCHHoJ/view?usp=drive_link) <br>


## 3. 사용 기술

Python, Pandas, NumPy, PyTorch, Scikit-learn

<br>

## 4. 역할

- 데이터 수집 및 전처리

YouTube Data API를 활용하여 분석 목적에 맞는 댓글 데이터를 수집하고, 불필요한 노이즈를 제거하는 정제 작업을 수행했습니다.

- 모델 학습 및 검증

팀원들과의 협의를 통해 모델의 목표가 되는 6가지 감정 분류 체계를 수립했습니다. 이후, 정제된 데이터로 모델을 학습시키고 새로운 댓글에 대한 추론 결과를 확인하며 모델의 실효성을 검증했습니다.

- 인사이트 시각화 및 발표 자료

모델의 분석 결과를 바탕으로 핵심 인사이트를 도출하고, 이를 레이더 차트, 시계열 그래프 등으로 시각화하고, 프로젝트의 전 과정을 담은 최종 발표자료(PPT)를 작성하여 결과를 효과적으로 전달했습니다.

<br>

## 5. 결과 & 성과

모델 성능 (정확도, F1-score, AUC 등)

인사이트 (예: "고객 세그먼트별 구매 패턴 발견")

시각화 이미지나 그래프 첨부

[발표 자료](https://docs.google.com/presentation/d/1yRYz8jSv_VwHJIk6l3nCtfO1VoO1Jxt4/edit?usp=sharing&ouid=116413280130938266406&rtpof=true&sd=true)
