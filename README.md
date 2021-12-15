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
    - [loss 선택과 설정](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class3/base_model_configuration.ipynb#scrollTo=byU0eVWW47W9)
    - [metric 선택과 설정](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class3/base_model_configuration.ipynb#scrollTo=WCwdsoZC47PQ)
    - [batch_size 결정](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class3/base_model_configuration.ipynb#scrollTo=d4Jwyvmh47I2)
    - callback
        - [학습 중 loss 그리기](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class10/keras_callback.ipynb#scrollTo=mFCNnJtknkQo)
        - [학습 중 조기 종료](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class10/keras_callback.ipynb#scrollTo=-GdXVYClnj-d)
        - [학습 중 모델 저장](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class10/keras_callback.ipynb#scrollTo=Q3pS1ZDznkcf)
        - [학습 중 학습율 조정](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class10/keras_callback.ipynb#scrollTo=ePzRsc2ATPAm)
    - [모델 저장과 로딩](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class2/base_dnn_code_in_keras.ipynb#scrollTo=y5pWvzXVKA5X)
    - [모델 모양 보기](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class2/base_dnn_code_in_keras.ipynb#scrollTo=qUvAijAPoZEt)

<br>

- 데이터
    - [http 데이터 다운로드](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class8/template_text_sequence_data_prediction.ipynb#scrollTo=S85WJqNmOp7W&line=1&uniqifier=1)
    - [속성 데이터 로딩](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class4/normalization_and_standardization.ipynb#scrollTo=a8JBf-TC5AWk)
    - [영상 데이터 로딩](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class7/template_image_data_transfer_learning_classification.ipynb#scrollTo=0Whz-eAEwqCl)
    - [영상 데이터 증강](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class7/template_image_data_transfer_learning_classification.ipynb#scrollTo=0Whz-eAEwqCl)
    - 데이터 train/test 분리
        - [수작업으로](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class4/data_split_apply_valid.ipynb#scrollTo=smFdOX0J5JML)
        - [scikit으로](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class4/data_split_apply_valid.ipynb#scrollTo=F7LLvEfI7hEx)
    - [validation 데이터 설정](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class4/data_split_apply_valid.ipynb#scrollTo=I67s099Q-YJd)
    - 데이터 섞기
        - [X, Y 분리 전에](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class4/data_split_apply_valid.ipynb#scrollTo=sfiCFU6gQpKT)
        - [X, Y 분리 후에](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class4/data_split_apply_valid.ipynb#scrollTo=cuHu0EKcRD27)
    - [분류 레이블링 데이터 준비](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class7/template_attribute_data_classification.ipynb#scrollTo=qDu8wpKXq7kV)
    - Normalization
        - [속성 데이터](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class4/normalization_and_standardization.ipynb#scrollTo=nXhrrOwgjcB9)
        - [영상 데이터](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class4/normalization_and_standardization.ipynb#scrollTo=PZRtMNZUgaA8)
    - Standardization
        - [속성 데이터](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class4/normalization_and_standardization.ipynb#scrollTo=6EgZXbG_qJnF)
        - [영상 데이터](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class4/normalization_and_standardization.ipynb#scrollTo=B8woQFKAqL2v)
    - [커스텀 data generator](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/etc/custom_data_generator.ipynb)
<br>

- 튜닝
    - [모델의 크기와 성능](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class11/performance.ipynb#scrollTo=vT-CKHGIXjwc)
    - [데이터 양과 성능](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class11/performance.ipynb#scrollTo=xSbcHthvYpA9)
    - [normalization과 성능](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class11/performance.ipynb#scrollTo=IrLPWr5qg1hk)
    - 오버피팅 처리법
        - [drop out](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class12/treating_overfitting.ipynb#scrollTo=JXugk5XL4Vcg)
        - [batch normalization](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class12/treating_overfitting.ipynb#scrollTo=InNqbyKae5rY)
        - [regularization](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class12/treating_overfitting.ipynb#scrollTo=BPXW3Kez4Y33)
        - [영상 데이터 증강](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class7/template_image_data_transfer_learning_classification.ipynb#scrollTo=0Whz-eAEwqCl)

<br>

- 시각화
    - 모델
        - [loss 그리기](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class6/draw_loss_and_metric.ipynb#scrollTo=iw9kjMSVP8Nf)
        - [metric 그리기](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class6/draw_loss_and_metric.ipynb#scrollTo=XwWJBXidP98b)
        - [회귀 예측 결과 그리기](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class7/template_attribute_data_regression.ipynb#scrollTo=ozcBPXF7w7B1)
        - [분류 예측 결과 그리기](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class7/template_attribute_data_classification.ipynb#scrollTo=ozcBPXF7w7B1)
    - 데이터
        - [영상 데이터 그리기](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class6/draw_image_data.ipynb#scrollTo=DS-e_vx0YYE1)
        - [순차열 데이터 그리기](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class6/draw_sequence_datq.ipynb#scrollTo=PQZRLzI5ZN2_)
        - [데이터 분포 그리기](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class4/normalization_and_standardization.ipynb#scrollTo=nXhrrOwgjcB9)
    - 결과
        - [ROC 커브 그리기](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class6/roc_and_auc_confusion_matric.ipynb#scrollTo=RZoV-4IDj1bw)
        - [confusion matrix 그리기](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class6/roc_and_auc_confusion_matric.ipynb#scrollTo=BYOG3koCj1bx)

<br>

- 템플릿
    - 속성 데이터
        - [회귀 Template](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class7/template_attribute_data_regression.ipynb#scrollTo=giMgHzNY8861&line=1&uniqifier=1)
        - [분류 Template](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class7/template_attribute_data_classification.ipynb#scrollTo=giMgHzNY8861)
    - 영상 데이터
        - [회귀 by 전이학습 Template](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/etc/template_image_data_transfer_learning_regression.ipynb)
        - [분류 by 전이학습 Template](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class7/template_image_data_transfer_learning_classification.ipynb#scrollTo=Sv47DFcMmPRe)
    - 순차열 데이터
        - [회귀 Template](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class9/template_numeric_sequence_data_prediction.ipynb#scrollTo=mZAFnuGfwqy-)
        - [분류 Template](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class9/template_numeric_sequence_data_classification.ipynb#scrollTo=mZAFnuGfwqy-)
    - 텍스트 데이터
        - [회귀 Template](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class8/template_text_sequence_data_prediction.ipynb#scrollTo=h2T83cSMqzM5)
        - [분류 Template](https://colab.research.google.com/github/dhrim/keras_howto_2021/blob/master/class8/template_text_sequence_data_classification.ipynb#scrollTo=-bTCweaZO2UH)

<br>

