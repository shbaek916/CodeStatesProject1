# CodeStates Project 1
## _스타크래프트 2 승패 정량적 분석_

#### 개요 & 프로젝트의 목적

실시간 전략 게임인 스타크래프트는 일대일 혹은 다대다의 승부에서 각자의 종족을 선택해 승부를 겨루는 게임입니다. 스타크래프트는 플레이하게 되는 맵의 지형과 전략이 더욱 중요한 게임이지만, 정량적인 분석이 필요없는 것은 아닙니다. 게임내 자원관리, 유닛 생산량, 특정 활동의 횟수, 이런 것들은 플레이어가 실시간으로 세우는 전략을 어떻게 실행하고 있느냐, 즉 플레이어의 ‘피지컬’ 을 판단할 수 있는 지표가 되기도 합니다. 따라서 이런 지표들을 선정하여 플레이어들 스스로 실력을 상승시키는데 선택과 집중을 할 수 있게 돕는 것이 이번 프로젝트의 목적입니다.

#### 본 레포지토리에 대한 설명

###### Analysis_and_Modeling.ipynb 
- 본 프로젝트의 본격적 분석 및 승패 예측
###### Preprocessing_1_data_split.ipynb
- 본래 670만행의 거대한 로그데이터이기에 EDA 와 Data Wrangling에 용이하게 원본데이터의 game_id 값에 따라 나눔
###### Preprocessing_2_data_organizing(1).ipynb
- Train 데이터의 분석하고자 하는 특성을 추출
###### Preprocessing_2_data_organizing(1)_test_data.ipynb
- Test 데이터의 분석하고자 하는 특성을 추출
###### Preprocessing_2_data_organizing(2).ipynb
- 본격적 분석에 앞서 데이터 전처리 진행
###### Project 1. 스타크래프트2 승패의 정량적 분석 [백송하].docx
- 코드스테이츠 제출용 기획서

#### 활용된 데이터 
- 2020년 4월 종료된 Blizzard 사의 Starcraft II 게임의 행동 데이터 분석 대회 (DACON)
- https://dacon.io/competitions/official/235583/overview/description
