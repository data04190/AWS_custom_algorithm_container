# custom_algorithm_container

<br>

#### container 파일 구조

```
.
|-- Dockerfile
|-- build_and_push.sh
`-- ESN
    |-- nginx.conf
    |-- predictor.py
    |-- serve
    |-- train
    `-- wsgi.py
 ```
 
 <br>
 
#### SageMaker에서 학습 실행 파일 구조
 
 ```
 /opt/ml
|-- input
|   |-- config
|   |   |-- hyperparameters.json
|   |   `-- resourceConfig.json
|   `-- data
|       `-- <channel_name>
|           `-- <input data>
|-- model
|   `-- <model files>
`-- output
    `-- failure
 
 
 ```
