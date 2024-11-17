# SKN06-2nd-4Team
SKN6기 2nd 단위 프로젝트 - 공인용, 김동명, 박유나, 임연경
## 가디언즈 오브 독산
<img src="https://postfiles.pstatic.net/20140724_24/sound_tel_1406201694894NzGTt_PNG/Screenshot_2014-07-24-20-25-03_edit.png?type=w1" alt="image" width="200" height="300"/>

### 팀원
| 공인용 | 김동명 | 박유나 | 임연경 |
|--|--|--|--|
| <img src="https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAxODA0MTFfMTM0%2FMDAxNTIzNDU0NzkwNDE5.gEK35xFgCX9vYBn5oOJyWuh2e5pbuhlSbfdl6poV5uEg.Mv_Dfnxo30cnaT6L6CRO1qnHuhw-w2-IOrbCvdavhJ8g.JPEG.hong5395%2F3e9932eb44c7e5d95e3380f0b3850a10849e64a53fc218b5f937de3f8aa32c7d179cdaa4ff41.jpg&type=sc960_832" alt="image" width="200" height="250"/>| <img src="https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAxNzAzMDVfMTA2%2FMDAxNDg4Njk1MjMzMzM5.n8IyNuI2bfb9ahCzK5BuXarECmC0kAgwXAQ_VqnVfvkg.YVo_NXVr0Yum_arFadeksjm5EK2llgXS7c5_gdAAyk0g.JPEG.herotime01%2Fmms411-r9_shop1_151309.jpg&type=sc960_832" alt="image" width="200" height="250"/>| <img src="https://search.pstatic.net/sunny/?src=https%3A%2F%2Fi.namu.wiki%2Fi%2FHTd0cQVU-2HsObW-meRcGxERbzgr80e3y0K2IkUPVuAtCAQgoN684suvdC3B3vAr6G_lT_XJk4j5k7l-_7sLbg.webp&type=sc960_832" alt="image" width="200" height="250"/>|<img src="https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAxODA1MjVfMTMz%2FMDAxNTI3MTk1NDA2NDY4.52sHvf5xhDFsa547Q0XppzIAaz_LuXEm1vIkHcXev8Ag.dxIsd79lNL_5QekTes5_Agf4EzveLb7L1Ub-EHP738Ag.JPEG.loyh%2FDSC01289.JPG&type=a340" alt="image" width="200" height="250"/>|

</br></br></br>

## 💳 신용카드 이용 고객데이터 분석 및 이탈 예측 모델 💳

### ✔️ 개발 기간
2024.11.14~2024.11.15(총 2일)

### ✔️ 프로젝트 필요성 (배경)
금융 서비스 시장에서 고객 이탈 방지는 수익성 유지와 경쟁력 강화를 위해 필수적이다. 신용카드 사용 고객의 이탈 패턴을 이해하고, 효과적인 고객 유지 전략을 세우기 위해 이탈 예측 모델이 필요하다. 이를 통해 금융 기관은 데이터 기반 의사결정을 강화하고, 고객 맞춤형 마케팅 전략을 수립할 수 있다.

### ✔️ 프로젝트 목표
신용카드 사용 고객의 데이터를 분석하여 이탈 가능성을 예측하는 모델을 개발하고, 이탈에 영향을 미치는 원인을 알아냄으로써 경제 시장에서의 고객 관리 전략을 개선할 수 있다.


</br>

#### ✔️ Stacks
![Discord](https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)    

![Python](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white) 
![Numpy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=NumPy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
<img src="https://img.shields.io/badge/scikitlearn-%23F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>

![Streamlit](https://img.shields.io/badge/streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white) 
</br>

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)



#### ✔️ Requirements

streamlit == 1.39.0
pymysql == 1.1.1
pandas == 2.2.3
openpyxl == 1.1.0
sqlalchemy == 2.0.35
configparser == 7.1.0
matplotlib == 3.9.2
xlrd == 2.0.1
seaborn == 0.13.2
joblib == 1.3.2
scikit-learn == 1.3.1
numpy == 1.26.0
xgboost == 1.7.6


## 데이터 전처리
### ✔️ 변수 정의
[Google 스프레드시트 보기](https://docs.google.com/spreadsheets/d/1PvMto9SCOenoNsXg_mjzhMyAeArdpVEP5e5ZlOuftFI/edit?usp=sharing)

### ✔️ EDA(탐색적 데이터 분석)
![image](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/EDA.png)
### ✔️ 결측치 처리
⭐️ 문자열 형식으로 된 education_level, marital_status, income_category에서 Unknown이라는 결측치 발생 ⭐️
| education_level | marital_status | income_category |
|--|--|--|
| ![image](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/%EA%B2%B0%EC%B8%A1%EC%B9%98%20%ED%95%99%EB%B2%8C.png) | ![image](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/%EA%B2%B0%EC%B8%A1%EC%B9%98%20%EA%B2%B0%ED%98%BC.png) | ![image](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/%EA%B2%B0%EC%B8%A1%EC%B9%98%20%EC%9E%90%EC%82%B0.png) |
| SimpleImputer(최빈값) | SimpleImputer(최빈값) | 사용자 정의 imputer(가중대체) |
| unkown의 비율이 나머지에 비에 높지 않음 | unkown의 비율이 나머지에 비에 높지 않음 | unkown의 비율이 나머지에 비에 높음 |
| Graduate가 가장 많은 비율(30.89%)을 차지 | Married가 가장 높은 비율(46.28%)을 차지 | 각각 나머지 자료의 비율에 따라 랜덤으로 분배 |
</br>
👉🏻 우리가 정의한 imputer
</br>



```
 Class ProportionalImputer(BaseEstimator, TransformerMixin):
    def __init__(self, columns):
        self.columns = columns
        self.fill_values = {}

    def fit(self, X, y=None):
        for column in self.columns:
            value_counts = X[column].value_counts(normalize=True)
            self.fill_values[column] = (value_counts.index, value_counts.values)
        return self

    def transform(self, X):
        X = X.copy()
        for column in self.columns:

            nan_count = X[column].isna().sum()
            if nan_count > 0:
                fill_values = np.random.choice(
                    self.fill_values[column][0], size=nan_count, p=self.fill_values[column][1]
                )
                X.loc[X[column].isna(), column] = fill_values
        return X
```




### ✔️ 이상치 처리

![image](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/boxplot.png)


```
def find_outliers(df, column_name, whis=1.5):
    q1, q3 = df[column_name].quantile(q=[0.25, 0.75])
    iqr = q3 - q1
    iqr *= whis
    return df.loc[~df[column_name].between(q1 - iqr, q3 + iqr)]
```




</br>
⭐️ 발생한 여러 이상치들 중 결과에 영향을 거의 미치지 않을 것같은 이상치 삭제 => ["age", "total_trans_cnt"] 두 칼럼의 이상치를 삭제하기로 결정 ⭐️
</br>





```
def delete_outliers(df, columns, whis=1.5):
    index_list = []
    _df = df.copy()
    
    for col in columns: 
        outliers_column_index = find_outliers(df, col, whis=whis)
        index_list.extend(outliers_column_index.index)
        
        
    _df = _df.drop(index=index_list)
        
    _df.reset_index(drop=True, inplace=True)
    
    return _df

outlier_columns = ["age", "total_trans_cnt"]
df = delete_outliers(df, outlier_columns)
```





### ✔️ Feature Engineering
⭐️ 문자열 자료들을 숫자형으로 변경하기 위해 진행 ⭐️
⭐️ 각각의 인코딩 방법을 학습하여 따로 .pkl로 저장 ⭐️
1. 라벨 인코딩(Label Encoding) 
> 'gender'
> 
> 이진 변수의 경우 모델 성능에 큰 차이가 없으므로, 간단히 라벨 인코딩을 사용하기로 함.
> 
2. 순서 인코딩 (Ordinal Encoding)
> 'education_level', 'income_category'
>
> 학력과 소득과 관련된 자료는 자료량이 아닌 해당 index로 순서를 결정하기 위함.
> 
3. mapping
> 'churn'
>
> 이탈한 고객을 1로 설정하고 이탈하지 않은 고객을 0으로 설정해 자료의 분석을 쉽게할 수 있도록 함.
> 
4. 원핫 인코딩(One-Hot encoding)
> 'marital_status', 'card_category'
> 
> 순서가 없고 각 값이 독립적인 범주형 데이터으로서 순서나 크기 정보 없이 각각 독립적인 특성으로 변환되므로, 머신러닝 모델에서 더 잘 해석될 가능성이 있다고 보아 OneHot 인코딩 하기로 결정.
>

## 모델 학습 결과서
### 모델 평가에 사용된 평가 지표
- 'id', 'Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_Months_Inactive_12_mon_1', 'Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_Months_Inactive_12_mon_2' 을 제외한 다른 지표
> 'id' : 모든 행들이 가지고 있는 고유의 값으로 평가에는 도움이 되지 않음.
> 
> 'Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_Months_Inactive_12_mon_1', 'Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_Months_Inactive_12_mon_2' : 이 지표들은 이미 기존 모델에서 계산된 확률 값이므로, 새 모델에 포함시키면 편향이나 과적합을 유발할 수 있음.


### 과정
- 전체적으로 어떤 모델이 적합할지 확인
  ```
    from tqdm import tqdm
    
    from sklearn.linear_model import LogisticRegression
    from sklearn.tree import DecisionTreeClassifier
    from sklearn.ensemble import RandomForestClassifier
    from sklearn.ensemble import GradientBoostingClassifier
    from xgboost import XGBClassifier, plot_importance
    from sklearn.svm import SVC
    from sklearn.neighbors import KNeighborsClassifier
    
    import matplotlib.pyplot as plt
    models = { 
        # Logistic Regression model
        "Logistic Regression": LogisticRegression(),
        # Decision Tree model
        "Decision Tree Classifier": DecisionTreeClassifier(),
        # Random Forest model
        "Random Forest": RandomForestClassifier(),
        # Gradient Boosting model
        "Gradient Boosting": GradientBoostingClassifier(),
        # XGBoost model
        "XGBoost": XGBClassifier(),
        # SVM(Support Vector Machine)
        "SVC": SVC(),
        # KNN(K-Nearest Neighbors)
        "KNeighborsClassifier": KNeighborsClassifier(),
    }
    
    
    for name, model in tqdm(models.items(), desc="Training Models", total=len(models)):
        # 모델 훈련
        model.fit(X_train, y_train)
        # 모델 평가
        score = model.score(X_test, y_test)
        # 모델 검증
        model_pred = model.predict(X_test)
        # 모델 정확도
        tqdm.write(f">>> {name} : 정확도 {score:.2%}\n")

  ```





    
  ![image](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D%20%EC%B2%AB%EA%B2%B0%EA%B3%BC.png)
- 우수 모델 4가지를 선택해 파라미터 설정 등 자세한 분석 시행
  ##### Decision Tree Classifier : 정확도 93.78%
  - 주요 파라미터
    > criterion: 노드 분할 기준
    > 
    > max_depth: 각 결정 트리의 최대 깊이를 설정
    > 
    > min_samples_split: 노드를 분할하기 위한 최소 샘플 수
    > 
    > min_samples_leaf: 리프 노드의 최소 샘플 수
    > 
    > max_features: 각 트리가 학습할 때마다 사용할 특성(feature)의 수
    
    ```
    
    from sklearn.tree import DecisionTreeClassifier
    
    # 1. 학습 및 예측
    X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)
    
    
    
    tree = DecisionTreeClassifier()
    
    tree.fit(X_train, y_train)
    
    # 2. 모델 평가
    # Train set + Test set 평가
    y_train_pred_tree = tree.predict(X_train)
    y_train_proba_tree= tree.predict_proba(X_train)[:, 1]
    
    y_test_pred_tree = tree.predict(X_test)
    y_test_proba_tree= tree.predict_proba(X_test)[:, 1]
    
    # 혼동 행렬 시각화 (테스트 데이터)
    cm_test = confusion_matrix(y_test, y_test_pred_tree)
    plt.figure(figsize=(6, 4))
    sns.heatmap(cm_test, annot=True, fmt="d", cmap="Blues", cbar=False)
    plt.xlabel("예측")
    plt.ylabel("정답")
    plt.title("Confusion Matrix - Decision Tree (Test Set)")
    plt.show()
     
    evaluate("Train - Decision Tree", y_train, y_train_pred_tree, y_train_proba_tree)
    evaluate("Test - Decision Tree", y_test, y_test_pred_tree, y_test_proba_tree)
    
    # 3. 특성 중요도 계산 및 시각화
    fi = tree.feature_importances_
    fi_series = pd.Series(fi, index=df.drop(columns="churn").columns).sort_values(ascending=False)
    
    # 특성 중요도 시각화
    plt.figure(figsize=(10, 6))
    sns.barplot(x=fi_series, y=fi_series.index)
    plt.title("Feature Importances in Decision Tree")
    plt.xlabel("Importance")
    plt.ylabel("Feature")
    plt.show()
    
    # 4. 최적의 매개변수 구하기 - GridSearchCV
    params = {
        'criterion': ['gini', 'entropy'],  # 노드 분할 기준
        'max_depth': [None, 10, 20, 30],   # 각 결정 트리의 최대 깊이를 설정
        'min_samples_split': [2, 10, 20],  # 노드를 분할하기 위한 최소 샘플 수
        'min_samples_leaf': [1, 5, 10],    # 리프 노드의 최소 샘플 수
        'max_features': [None, 'sqrt', 'log2']  # 각 트리가 학습할 때마다 사용할 특성(feature)의 수
    }
    
    gs_tree = GridSearchCV(
        estimator=tree,          
        param_grid=params,  
        scoring=scoring,
        refit='accuracy',
        cv=5,             
        n_jobs=-1,         
    )
    
    gs_tree.fit(X_train, y_train)
    
    # 5. Best Model: 최적의 하이파라미터로 만든 모델
    best_param_tree = gs_tree.best_params_
    best_model_tree = gs_tree.best_estimator_
    
    best_y_pred_tree = best_model_tree.predict(X_test)
    best_y_proba_tree= best_model_tree.predict_proba(X_test)[:, 1]
    
    # score 기록 
    model_box['decision_tree'] = evaluate("Best - Decision Tree", y_test, best_y_pred_tree, best_y_proba_tree)
    ```
    
  ##### Random Forest : 정확도 95.65%
    
    - 주요 파라미터
        > n_estimators: 부스팅 단계의 수 = 모델이 생성할 트리 개수
        > 
        > max_depth: 각 결정 트리의 최대 깊이를 설정
        > 
        > max_features: 각 트리가 학습할 때마다 사용할 특성(feature)의 수
        >
        ```
        from sklearn.ensemble import RandomForestClassifier

        # 1. 학습 및 예측
        X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)
        
        rf = RandomForestClassifier()
        
        rf.fit(X_train, y_train)
        
        # 2. 모델 평가
        # Train set + Test set 평가
        y_train_pred_rf = rf.predict(X_train)
        y_train_proba_rf= rf.predict_proba(X_train)[:, 1]
        
        y_test_pred_rf = rf.predict(X_test)
        y_test_proba_rf= rf.predict_proba(X_test)[:, 1]
        
        # 혼동 행렬 시각화 (테스트 데이터)
        cm_test = confusion_matrix(y_test, y_test_pred_rf)
        plt.figure(figsize=(6, 4))
        sns.heatmap(cm_test, annot=True, fmt="d", cmap="Blues", cbar=False)
        plt.xlabel("예측")
        plt.ylabel("정답")
        plt.title("Confusion Matrix - Random Forest (Test Set)")
        plt.show()
        
        evaluate("Train - Random Forest", y_train, y_train_pred_rf, y_train_proba_rf)
        evaluate("Test - Random Forest", y_test, y_test_pred_rf, y_test_proba_rf)
        
        # 3. 특성 중요도 계산 및 시각화
        fi = rf.feature_importances_
        fi_series = pd.Series(fi, index=df.drop(columns="churn").columns).sort_values(ascending=False)
        
        # 특성 중요도 시각화
        plt.figure(figsize=(10, 6))
        sns.barplot(x=fi_series, y=fi_series.index)
        plt.title("Feature Importances in Random Forest")
        plt.xlabel("Importance")
        plt.ylabel("Feature")
        plt.show()
        
        # 4. 최적의 매개변수 구하기 - GridSearchCV
        params = {
            'n_estimators': [100, 200, 300],    # 결정 트리(Decision Tree)의 개수
            'max_depth': [5, 10, 15],           # 각 결정 트리의 최대 깊이를 설정
            'max_features': ['sqrt', 'log2']    # 각 트리가 학습할 때마다 사용할 특성(feature)의 수
        }
        gs_rf = GridSearchCV(
            estimator=rf,       
            param_grid=params,     
            scoring=scoring,
            refit='accuracy',
            cv=5,                      
            n_jobs=-1,             
        )
        
        gs_rf.fit(X_train, y_train)
        
        # 5. Best Model: 최적의 하이파라미터로 만든 모델
        best_param_rf = gs_rf.best_params_
        best_model_rf = gs_rf.best_estimator_
        
        best_y_pred_rf = best_model_rf.predict(X_test)
        best_y_proba_rf= best_model_rf.predict_proba(X_test)[:, 1]
        
        # score 기록 
        model_box['random_forest'] = evaluate("Best - Random Forest", y_test, best_y_pred_rf, best_y_proba_rf)
        ```
  

 
  ##### Gradient Boosting : 정확도 96.79%

    
    
    - 주요 파라미터
        > n_estimators: 부스팅 단계의 수 = 모델이 생성할 트리 개수
        > 
        > learning_rate: 학습률
        >
        > max_depth: 각 결정 트리의 최대 깊이를 설정
        > 
        > subsample: 각 트리 학습에 사용되는 샘플의 비율
        >
        ```
        from sklearn.ensemble import GradientBoostingClassifier
        
        # 1. 학습 및 예측
        X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)
        
        gb = GradientBoostingClassifier()
        
        gb.fit(X_train, y_train)
        
        # 2. 모델 평가
        # Train set + Test set 평가
        y_train_pred_gb = gb.predict(X_train)
        y_train_proba_gb= gb.predict_proba(X_train)[:, 1]
        
        y_test_pred_gb = gb.predict(X_test)
        y_test_proba_gb= gb.predict_proba(X_test)[:, 1]
        
        # 혼동 행렬 시각화 (테스트 데이터)
        cm_test = confusion_matrix(y_test, y_test_pred_gb)
        plt.figure(figsize=(6,4))
        sns.heatmap(cm_test, annot=True, fmt="d", cmap="Blues", cbar=False)
        plt.xlabel("예측")
        plt.ylabel("정답")
        plt.title("Confusion Matrix - Gradient Boosting (Test Set)")
        plt.show()
        
        evaluate("Train - Gradient Booting", y_train, y_train_pred_gb, y_train_proba_gb)
        evaluate("Test - Gradient Booting", y_test, y_test_pred_gb, y_test_proba_gb)
        
        # 3. 특성 중요도 계산 및 시각화
        fi = gb.feature_importances_
        fi_series = pd.Series(fi, index=df.drop(columns="churn").columns).sort_values(ascending=False)
        
        # 특성 중요도 시각화
        plt.figure(figsize=(10, 6))
        sns.barplot(x=fi_series, y=fi_series.index)
        plt.title("Feature Importances in Gradient Boosting")
        plt.xlabel("Importance")
        plt.ylabel("Feature")
        plt.show()
        
        # 4. 최적의 매개변수 구하기 - GridSearchCV
        params = {
            "n_estimators": [100, 200, 300],  #  부스팅 단계의 수 = 모델이 생성할 트리 개수
            "learning_rate": [0.1],  # 학습률
            "max_depth": [1, 2, 3, 4, 5],  # 각 결정 트리의 최대 깊이를 설정
            "subsample": [0.5, 0.7],  # 샘플링 비율
        }
        
        gs_gb = GridSearchCV(
            estimator=gb,           
            param_grid=params,   
            scoring=scoring,
            refit='accuracy',
            cv=5,                  
            n_jobs=-1,            
        )
        
        gs_gb.fit(X_train, y_train)
        
        # 5. Best Model: 최적의 하이파라미터로 만든 모델
        best_param_gb = gs_gb.best_params_
        best_model_gb = gs_gb.best_estimator_
        
        best_y_pred_gb = best_model_gb.predict(X_test)
        best_y_proba_gb= best_model_gb.predict_proba(X_test)[:, 1]
        
        # score 기록 
        model_box['gradient_boosting'] = evaluate("Best - Gradient Boosting", y_test, best_y_pred_gb, best_y_proba_gb)
        ```
 
 

 
 
    
  ##### XGBoost : 정확도 97.19%
    - 주요 파라미터
        > max_depth: 각 결정 트리의 최대 깊이를 설정
        >
        > learning_rate: 학습률
        > 
        > n_estimators: 부스팅 단계의 수 = 모델이 생성할 트리 개수
        > 
        > subsample: 각 트리의 훈련에 사용되는 샘플 비율
        > 
        > colsample_bytree: 각 트리의 훈련에 사용되는 피처 비율
        > 
        > gamma: 노드 분할에 대한 최소 손실 감소
        > 
        > reg_alpha: L1 정규화
        > 
        > reg_lambda: L2 정규화
        >
        ```
        from xgboost import XGBClassifier
          
        X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)
        
        xgb = XGBClassifier()
        
        xgb.fit(X_train, y_train)
        
        # 2. 모델 평가
        # Train set + Test set 평가
        y_train_pred_xgb = xgb.predict(X_train)
        y_train_proba_xgb= xgb.predict_proba(X_train)[:, 1]
        
        y_test_pred_xgb = xgb.predict(X_test)
        y_test_proba_xgb= xgb.predict_proba(X_test)[:, 1]
        
        # 혼동 행렬 시각화 (테스트 데이터)
        cm_test = confusion_matrix(y_test, y_test_pred_xgb)
        plt.figure(figsize=(6, 4))
        sns.heatmap(cm_test, annot=True, fmt="d", cmap="Blues", cbar=False)
        plt.xlabel("예측")
        plt.ylabel("정답")
        plt.title("Confusion Matrix - XGBoost (Test Set)")
        plt.show()
        
        evaluate("Train - XGBoost", y_train, y_train_pred_xgb, y_train_proba_xgb)
        evaluate("Test - XGBoost", y_test, y_test_pred_xgb, y_test_proba_xgb)
        
        # 3. 특성 중요도 계산 및 시각화
        fi = xgb.feature_importances_
        fi_series = pd.Series(fi, index=df.drop(columns="churn").columns).sort_values(ascending=False)
        
        # 특성 중요도 시각화
        plt.figure(figsize=(10, 6))
        sns.barplot(x=fi_series, y=fi_series.index)
        plt.title("Feature Importances in XGBoost")
        plt.xlabel("Importance")
        plt.ylabel("Feature")
        plt.show()
        
        # 4. 최적의 매개변수 구하기 - GridSearchCV
        params = {
            "max_depth":[1, 2, 3, 4, 5],            # 각 결정 트리의 최대 깊이를 설정
            'learning_rate': [0.1],                 # 학습률
            'n_estimators': [100, 200, 300],        # 부스팅 단계의 수 = 모델이 생성할 트리 개수
            'subsample': [0.5, 0.7],                # 각 트리의 훈련에 사용되는 샘플 비율
            'colsample_bytree': [0.5, 0.7, 1.0],    # 각 트리의 훈련에 사용되는 피처 비율
            'gamma': [0, 0.1],                      # 노드 분할에 대한 최소 손실 감소
            'reg_alpha': [0],                       # L1 정규화
            'reg_lambda': [0.1]                     # L2 정규화
        }
        gs_xgb = GridSearchCV(
            estimator=xgb,           
            param_grid=params,   
            scoring=scoring,
            refit='accuracy',
            cv=5,                  
            n_jobs=-1,            
        )
        
        gs_xgb.fit(X_train, y_train)
        
        # 5. 튜닝 : Best Model 찾기
        best_param_xgb = gs_xgb.best_params_
        best_model_xgb = gs_xgb.best_estimator_
        
        best_y_pred_xgb = best_model_xgb.predict(X_test)
        best_y_proba_xgb= best_model_xgb.predict_proba(X_test)[:, 1]
        
        # score 기록 
        model_box['xgboost'] = evaluate("Best - XGBoost", y_test, best_y_pred_xgb, best_y_proba_xgb)
        ```
 
 
 
 




|머신러닝 방법| Decision Tree Classifier | Random Forest | Gradient Boosting | XGBoost |
|--|--|--|--|--|
|Confusion Matrix| <img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/%EA%B2%B0%EC%A0%95%EB%82%98%EB%AC%B4-cm.png" alt="image" width="200" height="200"/>| <img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/%EB%9E%9C%EB%8D%A4%ED%8F%AC%EB%A0%88%EC%8A%A4%ED%8A%B8-cm.png" width="200" height="200"/>| <img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/gradient-cm.png" alt="image" width="200" height="200"/>|<img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/XGboost-cm.png" alt="image" width="200" height="200"/>|
|결과| <img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/%EA%B2%B0%EC%A0%95%EB%82%98%EB%AC%B4-%EA%B2%B0%EA%B3%BC.png" alt="image" width="300" height="150"/>| <img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/%EB%9E%9C%EB%8D%A4%ED%8F%AC%EB%A0%88%EC%8A%A4%ED%8A%B8-%EA%B2%B0%EA%B3%BC.png" width="300" height="150"/>| <img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/gradient-%EA%B2%B0%EA%B3%BC.png" alt="image" width="300" height="150"/>|<img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/XGboost-%EA%B2%B0%EA%B3%BC.png" alt="image" width="300" height="150"/>|
|특성중요도| <img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/%EA%B2%B0%EC%A0%95%EB%82%98%EB%AC%B4-%ED%8A%B9%EC%84%B1%EC%A4%91%EC%9A%94%EB%8F%84.png" alt="image" width="300" height="150"/>| <img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/%EB%9E%9C%EB%8D%A4%ED%8F%AC%EB%A0%88%EC%8A%A4%ED%8A%B8-%ED%8A%B9%EC%84%B1%EC%A4%91%EC%9A%94%EB%8F%84.png" width="300" height="150"/>| <img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/gradient-%ED%8A%B9%EC%84%B1%EC%A4%91%EC%9A%94%EB%8F%84.png" alt="image" width="300" height="150"/>|<img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/XGboost-%ED%8A%B9%EC%84%B1%EC%A4%91%EC%9A%94%EB%8F%84.png" alt="image" width="300" height="150"/>|
|하이퍼파라미터| <img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/%EA%B2%B0%EC%A0%95%EB%82%98%EB%AC%B4-%ED%95%98%EC%9D%B4%ED%8D%BC%ED%8C%8C%EB%9D%BC%EB%AF%B8%ED%84%B0.png" alt="image" width="200" height="160"/> | <img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/%EB%9E%9C%EB%8D%A4%ED%8F%AC%EB%A0%88%EC%8A%A4%ED%8A%B8-%ED%95%98%EC%9D%B4%ED%8D%BC%ED%8C%8C%EB%9D%BC%EB%AF%B8%ED%84%B0.png" alt="image" width="200" height="100"/> | <img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/gradient-%ED%95%98%EC%9D%B4%ED%8D%BC%ED%8C%8C%EB%9D%BC%EB%AF%B8%ED%84%B0.png" alt="image" width="200" height="150"/> | <img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/XGBoost-%ED%95%98%EC%9D%B4%ED%8D%BC%ED%8C%8C%EB%9D%BC%EB%AF%B8%ED%84%B0.png" alt="image" width="200" height="150"/> |

</br>
    ```
    
    # 여러 평가 지표 설정
    scoring = {
        'accuracy': make_scorer(accuracy_score),
        'precision': make_scorer(precision_score),
        'recall': make_scorer(recall_score),
        'f1': make_scorer(f1_score),
        'auc': make_scorer(roc_auc_score)
    }
    
    model_box = pd.DataFrame(columns=['decision_tree', 'random_forest', 'gradient_boosting', 'xgboost'],
                             index = ['accuracy','precision','recall','f1 score','auc'])
    
    def evaluate(title, y_real, y_pred, y_prob):
        acc = accuracy_score(y_real, y_pred)
        pre = precision_score(y_real, y_pred)
        rec = recall_score(y_real, y_pred)
        f1 = f1_score(y_real, y_pred)
        auc = roc_auc_score(y_real, y_prob)
        
        print(f"======= {title} =======")
        print('Accuracy : {:.6f}'.format(acc)) # 정확도 : 예측이 정답과 얼마나 정확한가
        print('Precision : {:.6f}'.format(pre)) # 정밀도 : 예측한 것 중에서 정답의 비율
        print('Recall : {:.6f}'.format(rec)) # 재현율 : 정답 중에서 예측한 것의 비율
        print('F1 score : {:.6f}'.format(f1)) # 정밀도와 재현율의 (조화)평균 - 정밀도와 재현율이 비슷할수록 높은 점수
        print('auc: {:.6f}'.format(auc))
        
        
        score_list = [acc,pre,rec,f1,auc]
        score_box = np.array(score_list)
        
        return score_box
    ```




![image](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/%EC%A0%95%ED%99%95%EB%8F%84.png)



### 최종 선정 모델
⭐️ 4가지 모델의 최적의 모델 이용 ⭐️
```

# 5. 평가
# Best Model 의 하이퍼파라미터
print(best_param_tree)
print(best_param_rf)
print(best_param_gb)
print(best_param_xgb)

# Best Model 들의 scoring
model_box
# 6. 모델 저장
import os
import joblib

directory = 'model/'
os.makedirs(directory, exist_ok=True)

joblib.dump(best_model_tree, os.path.join(directory, 'best_tree.pkl'))
joblib.dump(best_model_rf, os.path.join(directory, 'best_rf.pkl'))
joblib.dump(best_model_gb, os.path.join(directory, 'best_gb.pkl'))
joblib.dump(best_model_xgb, os.path.join(directory, 'best_xgb.pkl'))

# 저장된 모델과 파라미터 불러오기
model_tree = joblib.load('model/best_tree.pkl')
model_rf = joblib.load('model/best_rf.pkl')
model_gb = joblib.load('model/best_gb.pkl')
model_xgb = joblib.load('model/best_xgb.pkl')
```



### streamlit 결과
![image](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/%EC%8A%A4%ED%8A%B8%EB%A6%BC%EB%A6%BF%20%EC%8B%A4%ED%96%89%20%ED%99%94%EB%A9%B4%201.png)
![image](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/%EC%8A%A4%ED%8A%B8%EB%A6%BC%EB%A6%BF%20%EC%8B%A4%ED%96%89%20%ED%99%94%EB%A9%B4%202.png)
![image](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN06-2nd-4Team/blob/main/report/%EC%8A%A4%ED%8A%B8%EB%A6%BC%EB%A6%BF%20%EC%8B%A4%ED%96%89%20%ED%99%94%EB%A9%B4%203.png)

### 추후 계선 사항
- 전처리 pipline
- 예측 후 평가
  
'colsample_bytree': 1.0 
