# R : 2024-03-04
## Options
options(warn = -1)<br>
options(repr.plot.width=15, repr.plot.height=9)<br>
Sys.setlocale(category = "LC_ALL", locale = "ko_KR.UTF-8")

## 함수
ls() : 현재 선언되어 있는 변수명 확인<br>
rm() : 변수 제거<br>
example()<br>
runif() : 난수 생성<br>
sample() : 난수 생성, 중복 제거가 default<br>
seq() : 반복<br>
sort() : 정렬<br>
weekdays() : 요일 출력<br>
unique() : 중복 제거<br>
length() : 데이터의 길이<br>
grep() : 특정 문자열의 번지<br>
colnames(), rownames() : col의 이름, row의 이름 확인<br>
append() : 벡터 연결<br>
paste() : 문자열 연결<br>
cat(),print() : 출력<br>
substring() : 문자열 추출<br>
rbind() : 데이터 추가<br>
cbind() : 속성 추가<br>
unlist() : list형 제거<br>
na.omit() : NA 제거<br>
ifelse() : 삼항연산자<br>

### 차트
plot() : 산포도, 데이터의 관계를 확인<br>
hist() : Histogram, 빈도수 확인<br>

### 집합
union() : 합집합<br>
intersect() : 교집합<br>
setdiff() : 차집합<br>
setequal : 같은 집합인지 확인<br>
subset() : 부분 집합<br>

### 계산
sqrt() : 제곱근<br>
abs() : 절댓값<br>
trunc() : 소수점 이하 버림<br>
sum() : 합계<br>
mean() : 평균<br>
median() : 중앙값<br>
max() : 최댓값<br>
min() : 최솟값<br>
range() : 범위값<br>
sd() : 표준편차<br>
ncol() : Column 수<br>
nrow() : Row 수<br>

### 자료형 확인 함수
head()<br>
tail()<br>
str()<br>
summary()<br>
<br>
is.numeric() : 수치형<br>
is.integer() : 정수형<br>
is.double() : 실수형<br>
is.logical() : 논리형<br>
is.data.frame() : data.frame 확인<br>
is.matrix() : matrix 확인<br>
is.factor() : 숫자와 문자의 값을 동시에 보유한 Type<br>
is.vector() : vector 확인<br>
is.element() : 원소 존재 확인 여부<br>

### 자료형 변환
as.numeric()<br>
as.integer()<br>
as.logical()<br>
as.double()<br>
as.data.frame()<br>
as.factor()<br>
as.Date()<br>

## stringr package
str_length() : 문자열 길이<br>
str_c() : 문자열 연결<br>
str_sub() : 범위에 해당하는 문자열 생성(substring)<br>
str_split() : 구분자를 기준으로 문자열을 분리<br>
str_replace : 기존 문자열을 특정 문자열로 대치<br>
str_extract : 문자열에서 특정 문자열 패턴의 '첫번째' 문자열 추출<br>
str_extract_all() : 문자열에서 특정 문자열 추출<br>
str_locate() : 문자열에서 특정 문자열 패턴의 첫번째 위치 추출, 특정 문자열 앞 부분
으로만 Data 작업이 이루어져야 할 때 주로 사용<br>
str_locate_all() : 문자열에서 특정 문자열 패턴의 위치들 추출<br>

## 데이터 시각화 - plot() 인수
<img width="552" alt="스크린샷 2024-03-07 오후 5 47 27" src="https://github.com/lcy0512/R/assets/152368203/79a6ad5e-a3ac-4ab6-9eb7-f8dc6b432a66">
