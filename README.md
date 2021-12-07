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
- loss 선택 방법
- metric 선택 방법
- batch_size 결정 결정 
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
- 영상 데이터 로딩
- 영상 데이터 증강
- 영상 데이터를 사용한 모델 학습/평가/예측

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
- 속성 데이터 예측 템플릿
- 속성 데이터 분류 템플릿
- 영상 데이터 분류 템플릿

<br>

## 8회차. 텍스트 데이터 코드 템플릿
교육 바로 가기 : [교육자료](class8)
### 상세 내용
- 텍스트 데이터 임베딩
- 텍스트 데이터 분류 템플릿
- 텍스트 데이터 예측 템플릿

<br>

## 9회차. 순차열 데이터코드 템플릿
교육 바로 가기 : [교육자료](class9)
### 상세 내용
- 순차열 데이터 처리
- 순차열 데이터 예측
- 순차열 데이터 분류

<br>

## 10회차. callback
교육 바로 가기 : [교육자료](class10)
### 상세 내용
- 학습 중 로스 그리기
- 학습 중 조기 종료
- 학습 중 모델 저장
- 학습 중 학습율 조정

<br>

## 11회차. 성능 개선
교육 바로 가기 : [교육자료](class11)
### 상세 내용
- 성능의 이해
- 모델 크기와 성능
- 데이터 값 크기와 성능
- 입출력 관계와 성능
- 데이터 양과 성능

<br>

## 12회차. 오버피팅 처리
교육 바로 가기 : [교육자료](class12)
### 상세 내용
- 오버피팅의 이해
- Drop Out
- Batch Normalzation
- Regularization

<br>

# HowTo 바로 가기
- 모델 설정
    - [loss 선택과 설정](class3/base_model_configuration.ipynb)
    - [metric 선택과 설정](class3/base_model_configuration.ipynb)
    - [batch_size 결정](class3/base_model_configuration.ipynb)
    - callback
        - [학습 중 loss 그리기](class10/keras_callback.ipynb)
        - [early stopping](class10/keras_callback.ipynb)
        - [학습 중 모델 저장](class10/keras_callback.ipynb)
        - [학습 중 학습율 조정](class10/keras_callback.ipynb)
    - [모델 저장과/로딩](class2/base_dnn_code_in_keras.ipynb)
    - [모델 모양 보기](class2/base_dnn_code_in_keras.ipynb)

<br>

- 데이터
    - [http 데이터 다운로드](class8/template_text_sequence_data_prediction.ipynb)
    - [영상 데이터 로딩](class7/template_image_data_transfer_learning_classification.ipynb)
    - [영상 데이터 증강](class7/template_image_data_transfer_learning_classification.ipynb)
    - [데이터 train/test 분리](class4/data_split_apply_valid.ipynb)
    - [validation 데이터 설정](class4/data_split_apply_valid.ipynb)
    - [데이터 섞기](class4/data_split_apply_valid.ipynb)
    - [분류 레이블링 데이터 준비](class7/template_attribute_data_classification.ipynb)
    - [Normalization](class4/normalization_and_standardization.ipynb)
    - [Standardization](class4/normalization_and_standardization.ipynb)

<br>

- 튜닝
    - [모델의 크기와 성능](class11/performance.ipynb)
    - [데이터 양과 성능](class11/performance.ipynb)
    - [normalization과 성능](class11/performance.ipynb)
    - [성능 지표란](class11/performance.ipynb)
    - [오버피팅 처리법]
        - [drop out](class12/treating_overfitting.ipynb)
        - [batch normalization](class12/treating_overfitting.ipynb)
        - [regularization](class12/treating_overfitting.ipynb)
        - [영상 데이터 증강](class7/template_image_data_transfer_learning_classification.ipynb)

<br>

- 시각화
    - 모델
        - [loss 그리기](class6/draw_loss_and_metric.ipynb)
        - [metric 그리기](class6/draw_loss_and_metric.ipynb)
        - [회귀 예측 결과 그리기](class7/template_attribute_data_regression.ipynb)
        - [분류 예측 결과 그리기](class7/template_attribute_data_classification.ipynb)
    - 데이터
        - [영상 데이터 그리기](class6/draw_image_data.ipynb)
        - [순차열 데이터 그리기](class6/draw_sequence_datq.ipynb)
        - [데이터 분포 그리기](http://TODO:add_link)
    - 결과
        - [ROC 커브 그리기](class6/roc_and_auc_confusion_matric.ipynb)
        - [confusion matrix 그리기](class6/roc_and_auc_confusion_matric.ipynb)

<br>

- 템플릿
    - 속성 데이터
        - [회귀 Template](class7/template_attribute_data_regression.ipynb)
        - [분류 Template](class7/template_attribute_data_classification.ipynb)
    - 영상 데이터
        - [분류 by 전이학습 Template](class7/template_image_data_transfer_learning_classification.ipynb)
    - 순차열 데이터
        - [회귀 Template](class9/template_numeric_sequence_data_prediction.ipynb)
        - [분류 Template](class9/template_numeric_sequence_data_classification.ipynb)
    - 텍스트 데이터
        - [회귀 Template](class8/template_text_sequence_data_prediction.ipynb)
        - [분류 Template](class8/template_text_sequence_data_classification.ipynb)

<br>

