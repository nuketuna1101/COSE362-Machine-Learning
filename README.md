# COSE362-Machine-Learning
COSE362 기계학습 텀 프로젝트

3인 팀 텀프로젝트


### > 풀고자 하는 문제

교통환경을 고려한 교통사고 피해 강도의 예측



### > 시도해 본 기계학습 방법론

- One-hot encoding
- upsampling
- feature selection
- random forest
- k-fold cross validation
- multi-output logistic regression



### > 요약 및 복기

- 초기엔 교통사고 피해 강도 예측에 대한 교통 환경을 중점적으로 생각했으나, 프로젝트에서 최초 설정한 feature만으론 accuracy와 f1-score 두 마리의 토끼 다 놓치는 결과뿐이었습니다. 이 점에 유의하여 기존 교통 환경에 국한되어 있던 feature 뿐만 아니라 운전자 및 탑승자와 관련한 인적 속성과 관련한 feature를 추가하여 좀 더 일반화시킬 수 있는 방향으로 조정하였습니다.

- 추가적으로 발전시킨다면, NLP에서 center word에 대해 문맥을 반영하기 위해 앞뒤 단어를 살피듯이, '사고 발생 시점에 국한된' 제한적인 feature set에서 보다 전후사정을 반영한 시점의 feature나 운전자/동승자의 인적 속성 feature를 추가하는 방향이 좋을 것이라는 insight를 발견하였습니다.
