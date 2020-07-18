## Samsung2020-DeepLearning Regularization and Optimization (2020_07)

### 실습 시작하기

1. KAIST PC에 접속하기
    - 1차 과정
    ```
    ssh -X -p 2222 com**@143.248.159.**
    source ~/.bashrc
    ```    
    - 2차 과정
    ```
    ssh -x -p 2222 com**02&143.248.159.**
    source ~/.bashrc
    ```
    


2. Git repository clone 후 해당 폴더로 이동 
```
git https://github.com/JoonHyung-Park/Samsung2020_MLI_RegOptim.git
cd Samsung2020_MLI_RegOptim
```

3. 가상 환경 activate

~~conda env create -f env.yml~~
```
conda activate kaist_mli
```

4. Jupyter notebook 실행
```
jupyter notebook -port 9000(or 9999)
```
(1차 과정: 9000 , 2차 과정: 9999)
5. 첫번째 실습 파일 (01_01_without_regularization)로 이동합니다. 

