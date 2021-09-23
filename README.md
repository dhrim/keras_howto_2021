# Keras Howto

본 리파지터리는 한국기술교육대학교의 온라인평생교육원에서 개설한 'Hands-on Keras How-To'(TODO:add link)의 실습 자료이다.

<br>

# 회차별 교육 내용

## 1회차. 과정 소개
교육 바로 가기 : [교육자료](class1)
### 상세 내용
- 과정 소개
- 딥러닝 소개
- 실습 환경 소개

<br>

## 2회차. Keras 코드의 기본 구조
교육 바로 가기 : [교육자료](class2)
### 상세 내용
- 모델 구조 정의와 loss, optimizer 설정
- 모델 학습과 평가, 예측
- 모델의 저장과 로딩

<br>

## 3회차. 기본적인 모델 설정
교육 바로 가기 : [교육자료](class3)
### 상세 내용
- loss 설정
- metric 설정
- batch_size 설정
- 기타 설정

<br>

## 4회차. 데이터 준비
교육 바로 가기 : [교육자료](class4)
### 상세 내용
- 3가지 데이터 - train/validation/test 데이터
- 분리 방법
- 학습 시의 validation 데이터 설정
- 데이터 전처리

<br>

## 5회차. 영상 데이터 처리/증강
교육 바로 가기 : [교육자료](class5)
### 상세 내용
- ImageDataGenerator를 사용한 데이터 로딩
- ImageDataGenerator를 사용한 데이터 증강
- 학습에 ImageDataGenerator 적용

<br>

## 6회차. 시각화
교육 바로 가기 : [교육자료](class6)
### 상세 내용
- loss와 metric 그리기
- confusion matrix 그리기
- ROC 그리기
- 영상 데이터 그리기
- 순차열 데이터 그리기

<br>


## 7회차. 속성/영상 데이터 코드 템플릿
교육 바로 가기 : [교육자료](class7)
### 상세 내용
- 속성 데이터 분류 - CNN
- 속성 데이터 예측 - CNN
- 영상 데이터 분류 - CNN
- 영상 데이터 분류 - 전이학습

<br>

## 8회차. 텍스트 데이터 코드 템플릿
교육 바로 가기 : [교육자료](class8)
### 상세 내용
- 텍스트 데이터 분류 - RNN
- 텍스트 데이터 예측 - RNN

<br>

## 9회차. 순차열 데이터코드 템플릿
교육 바로 가기 : [교육자료](class9)
### 상세 내용
- 순차열 데이터 분류 - CNN
- 순차열 데이터 예측 - CNN
- 순차열 데이터 분류 - RNN
- 순차열 데이터 예측 - RNN

<br>

## 10회차. callback
교육 바로 가기 : [교육자료](class10)
### 상세 내용
- 오버피팅 발생 시 조기 중지(early stopping)
- 실시간으로 로스 보기
- 학습 중에 모델 저장
- 학습 중에 학습율 조정

<br>

## 11회차. 성능 개선
교육 바로 가기 : [교육자료](class11)
### 상세 내용
- 성능의 이해
- 입출력 관계와 성능
- 모델의 크기와 성능
- normalziation과 성능
- 학습율과 성능

<br>

## 12회차. 오버피팅 처리
교육 바로 가기 : [교육자료](class12)
### 상세 내용
- 오버피팅의 이해
- dorp out
- batch normalzation
- regularization

<br>

# 항목 별 HowTo 바로 가기

- 튜닝
    - [성능이란](http://TODO:add_link)
    - [모델의 크기와 성능](http://TODO:add_link)
    - [데이터 양과 성능](http://TODO:add_link)
    - [normalization과 성능](http://TODO:add_link)
    - [성능 지표란](http://TODO:add_link)
    - [오버피팅 이란](http://TODO:add_link)
    - [오버피팅 처리법](http://TODO:add_link)
        - [drop out](http://TODO:add_link)
        - [batch normalization](http://TODO:add_link)
        - [regularization](http://TODO:add_link)
    - [learning rate 조정](http://TODO:add_link)

<br>

- CASE 별 문제 해결
    - [CASE : 기반 코드의 오동작](http://TODO:add_link)
    - [CASE : 기반 코드의 학습 안됨](http://TODO:add_link)
    - [CASE : 커스텀 데이터 적용시 오류](http://TODO:add_link)
    - [CASE : 커스텀 데이터 학습 안됨](http://TODO:add_link)
    - [CASE : train 로스와 val 로스의 큰 차이](http://TODO:add_link)
    - [CASE : 초기에 오버피팅](http://TODO:add_link)
    - [CASE : 크게 출렁이는 로스](http://TODO:add_link)

<br>

- 시각화
    - [영상 데이터 그리기](http://TODO:add_link)
    - [순차열 데이터 그리기](http://TODO:add_link)
    - [데이터 분포 그리기](http://TODO:add_link)


<br>

- 템플릿
    - 속성 데이터
        - [회귀 Template](http://TODO:add_link)
        - [분류 Template](http://TODO:add_link)
    - 영상 데이터
        - [회귀 Template](http://TODO:add_link)
        - [분류 by CNN Template](http://TODO:add_link)
        - [분류 by 전이학습 Template](http://TODO:add_link)
    - 순차열 데이터
        - 숫자열    
            - [회귀 Template](http://TODO:add_link)
            - [분류 Template](http://TODO:add_link)
        - 문자열
            - [회귀 Template](http://TODO:add_link)
            - [분류 Template](http://TODO:add_link)
        - 단어열    
            - [회귀 Template](http://TODO:add_link)
            - [분류 Template](http://TODO:add_link)


