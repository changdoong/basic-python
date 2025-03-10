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

## airbnb_df
### Airbnb 숙소 관련 정보를 포함하고 있는 csv이다.
### 결측값, 이상치를 처리하는 방법을 공부한다.
> 사용 함수 정리
- info()
결측값 갯수를 확인한다.

- isna()
결측값 여부를 불린으로 반환

- any(axis=1)
행 기준으로 True가 있으면 True반환

- fillna()
결측값을 지정한 값으로 채움

- duplicated(subset='컬럼명')
지정한 열 기준으로 중복 여부 확인 

- drop_duplicates()
중복된 행 제거

- quantile()
지정한 사분위수 반환

- capitalize()
문자열의 첫 글자를 대문자로 반환

- split()
문자열을 지정한 구분자 기준으로 나눔

- strip()
문자열의 앞뒤 공백, 특수문자 제거

- replace()
  특정 값을 다른 값으로 치환

## patient_df
### 환자의  건강 관련 정보를 포함하고 있는 csv이다.
### 정규화, 표준화와 같은 새로운 값을 계산하는 방법을 공부한다.
> 사용 함수 정리
- round()
숫자(또는 열)의 값을 소수점 이하 지정한 자리수로 반올림

- cut(bins=[])
연속형 데이터를 지정한 구간(bins)으로 나누어 범주형으로 변환
