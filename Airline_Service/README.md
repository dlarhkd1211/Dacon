## 데이콘 베이직 Basic 

Competition : [항공사 고객 만족도 예측 경진대회](https://dacon.io/competitions/official/235871/overview/description)

###  배경


항공사 만족도에 관한 정보가 담긴 데이터셋을 통해 데이터 분석 대회에 입문해보세요.

다른 사람들과 실력을 겨뤄보며 데이터 분석 대회의 즐거움을 느껴보세요.
![image](https://user-images.githubusercontent.com/54428934/152941783-3a4dafca-de5b-4d9c-a32b-06fae275a80b.png)

### Submission Record
-----

| Day |    Model                                   | Score        | Rank                                      | Link        | Best |
| :---------:  | :-----------:                                | :-------------------: | :-------------------:                         |  -------------------: | :-------------------: |
| 1             | stacked_pred*0.2 + xgb_pred*0.2 + lgb_pred*0.3 + cat_pred * 0.3              | 0.552           | 58           |  [Link](https://github.com/dlarhkd1211/Dacon/blob/master/Airline_Service/day1_submission/stack_submission.csv)       | |
| 1             | xgb_pred            |0.553           | 58 |   [Link](https://github.com/dlarhkd1211/Dacon/blob/master/Airline_Service/day1_submission/xgb_submission.csv)|  |
||첫날 제출한 코드는 전처리 실수로 잘못된 예측이 진행되었음.||||
| 2             | stacked_pred*0.2 + xgb_pred*0.2 + lgb_pred*0.3 + cat_pred * 0.3              | 0.898           | 73           |  [Link](https://github.com/dlarhkd1211/Dacon/blob/master/Airline_Service/day2_submission/stack_submission.csv)       |✔ |
| 2            |lgb_pred            | 0.883           | 73           |  [Link](https://github.com/dlarhkd1211/Dacon/blob/master/Airline_Service/day2_submission/lgb_submission.csv)       | |
| 2             |cat_pred           | 0.893           | 73           |  [Link](https://github.com/dlarhkd1211/Dacon/blob/master/Airline_Service/day2_submission/cat_submission.csv)       | |
