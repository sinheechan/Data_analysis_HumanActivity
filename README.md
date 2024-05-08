# Data_analysis_HumanActivity

Kaggle 데이터 분석 과정을 담은 내용입니다.

상세한 분석 과정은 HumanActivity.ipynb 파일에 작성하였으니 참고 부탁드립니다 (_ _)

<br/>

## WorkFlow Summary

- DecisionTree, RandomForest 모델 별 파라미터 Defalt 값 정확도 측정

  : DecisionTree : 0.8571, RandomForest : 0.9220

- 각 모델 별 파라미터 최적화 값을 도출학기 위해 GridSearchCV를 활용한 max_depth 값에 따른 정확도 측정

- 각 파라미터 별 최고 정확도를 도출한 파라미터값에 대한 각 모델 별 정확도 측정

  : DecisionTree : 0.8771, RandomForest : 0.9231

- 파라미터 별 Feature 중요도의 변화 기록 후 모델 개선 반영 예정
