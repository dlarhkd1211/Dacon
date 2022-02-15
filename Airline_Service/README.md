## 데이콘 베이직 Basic 

Competition : [항공사 고객 만족도 예측 경진대회](https://dacon.io/competitions/official/235871/overview/description)

###  배경


항공사 만족도에 관한 정보가 담긴 데이터셋을 통해 데이터 분석 대회에 입문해보세요.

다른 사람들과 실력을 겨뤄보며 데이터 분석 대회의 즐거움을 느껴보세요.
![image](https://user-images.githubusercontent.com/54428934/152941783-3a4dafca-de5b-4d9c-a32b-06fae275a80b.png)

### Submission Record
-----

| Day |    Model                                   | Score        | Rank                                      | Best |
| :---------:  | :-----------:                                | :-------------------:  |  :-------------------: | :-------------------: |
| 1             | stacked_pred*0.2 + xgb_pred*0.2 + lgb_pred*0.3 + cat_pred * 0.3              | 0.552           | 58           |   |
| 1             | xgb_pred            |0.553           | 58 |    |
||첫날 제출한 코드는 전처리 실수로 잘못된 예측이 진행되었음.||||
| 2             | stacked_pred*0.2 + xgb_pred*0.2 + lgb_pred*0.3 + cat_pred * 0.3              | 0.898           | 73           | |
| 2            |lgb_pred            | 0.883           | 73           |   |
| 2             |cat_pred           | 0.893           | 73           |  |
| 3             | stacked_pred*0.1 + xgb_pred*0.3 + lgb_pred*0.3 + cat_pred * 0.3              | 0.925           | 87           |   |
| 3            |lgb_pred            | 0.924           | 87           |  |
| 3             |cat_pred           | 0.932          | 42           |  ✔ |
| 4             | stacked_pred*0.2 + xgb_pred*0.1 + lgb_pred*0.2 + cat_pred * 0.5              | 0.931           | -           |   |
| 4            |xgb_pred            | 0.92           | -           |  |
||score 0에 대한 처리, 모델 Random Search 진행 예정 ||||
| 5             | stacked_pred*0.2 + xgb_pred*0.2 + lgb_pred*0.3 + cat_pred * 0.3 + MinMaxScaler              | 0.91           | -           |   |
| 5            |cat_pred + MinMaxScaler            | 0.915           | -           |  |
| 5            |cat_pred + StandardScaler           | 0.93           | -           |  |
||score 0에 대한 처리, Scale data처리 진행, Random Search 진행 예정 ||||
