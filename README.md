# basic-python
기본 문법 실습 코드 및 알고리즘 연습 기록하는 레포지토리이다.

# 파일 설명
## loan_df
### 고객의 대출 관련 정보를 포함하고 있는 csv이다.
### 기본적으로 Dataframe을 다루는 방법을 공부한다.
> 사용 함수 정리
- describe()
기본 통계정보를 요약해서 보여준다.

- sort_values(by='원하는 컬럼명')
특정 컬럼을 기준으로 정렬해준다.

- set_index()
특정 컬럼을 인덱스로 설정한다.

- rename()
컬럼명 변경시 사용한다.
ex) rename(columns=new_columns)

- unique()
컬럼별로 존재하는 고유한 값을 확인한다.

- value_counts()
각 값이 몇 개씩 존재하는지 확인한다.
