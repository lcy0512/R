# R
2024-03-04 R
## Options
options(warn = -1)
options(repr.plot.width=15, repr.plot.height=9)
Sys.setlocale(category = "LC_ALL", locale = "ko_KR.UTF-8")

## 함수
ls() : 현재 선언되어 있는 변수명 확인
rm() : 변수 제거
example()
runif() : 난수 생성
sample() : 난수 생성, 중복 제거가 default
seq() : 반복
sort() : 정렬
weekdays() : 요일 출력
unique() : 중복 제거
length() : 데이터의 길이
grep() : 특정 문자열의 번지
colnames(), rownames() : col의 이름, row의 이름 확인
append() : 벡터 연결
paste() : 문자열 연결
cat(),print() : 출력
substring() : 문자열 추출
rbind() : 데이터 추가
cbind() : 속성 추가
unlist() : list형 제거
na.omit() : NA 제거
ifelse() : 삼항연산자

### 차트
plot() : 산포도, 데이터의 관계를 확인
hist() : Histogram, 빈도수 확인

### 집합
union() : 합집합
intersect() : 교집합
setdiff() : 차집합
setequal : 같은 집합인지 확인

### 계산
sqrt() : 제곱근
abs() : 절댓값
trunc() : 소수점 이하 버림
sum() : 합계
mean() : 평균
median() : 중앙값
max() : 최댓값
min() : 최솟값
range() : 범위값
sd() : 표준편차
ncol() : Column 수
nrow() : Row 수

### 자료형 확인 함수
head()
tail()
str()
summary()

is.numeric() : 수치형
is.integer() : 정수형
is.double() : 실수형
is.logical() : 논리형
is.data.frame() : data.frame 확인
is.matrix() : matrix 확인
is.factor() : 숫자와 문자의 값을 동시에 보유한 Type
is.vector() : vector 확인
is.element() : 원소 존재 확인 여부

### 자료형 변환
as.numeric()
as.integer()
as.logical()
as.double()
as.data.frame()
as.factor()
as.Date()

## stringr package
str_length() : 문자열 길이
str_c() : 문자열 연결
str_sub() : 범위에 해당하는 문자열 생성(substring)
str_split() : 구분자를 기준으로 문자열을 분리
str_replace : 기존 문자열을 특정 문자열로 대치
str_extract : 문자열에서 특정 문자열 패턴의 '첫번째' 문자열 추출
str_extract_all() : 문자열에서 특정 문자열 추출
str_locate() : 문자열에서 특정 문자열 패턴의 첫번째 위치 추출, 특정 문자열 앞 부분으로만 Data 작업이 이루어져야 할 때 주로 사용
str_locate_all() : 문자열에서 특정 문자열 패턴의 위치들 추출