# airplane_delay_prediction

항공기 연착 예측을 위한 binary classification 프로젝트입니다.  
해당 프로젝트는 Kaggle에 게시된 Dataset을 가지고 진행되었습니다.  

- Catboost 모델을 사용한 이유  
    - 범주형(categorical) feature의 인코딩이 필요하지 않음  
    -  hyper-parameter tuning의 간소화
    -  연산 속도가 빠름 
- PDP, shap 모듈을 통한 예측 모델의 해석
