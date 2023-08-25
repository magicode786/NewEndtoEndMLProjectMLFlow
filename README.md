# NewEndtoEndMLProjectMLFlow
There was some issue with EndtoEndMLProjectMLFlow repo so NewEndtoEndMLProjectMLFlow created

steps to implement this projects from scratch
1. Create Git hub repo 
2. git clone this repo 
3. update template.py to create folder structure #1st commit
4. Update requirements.txt 
5. update setup file  #2nd commit
6. data_ingestion commit #3rd commit
7. Data_Validation commit #4th commit

repeat the following steps for all the modules/stages
1. Update logging info in src/projectname/_init_.py 
2. Update config.yaml, params.yaml, schema.yaml
3. Update config_entity.py
4. update config.py #configuration manager
4. update components #data_ingestion, data_validation, data_transformation, model_training, model_evaluation
5. update pipeline stages #data_ingestion, data_validation, data_transformation, model_training, model_evaluation
6. update main.py


## ml flow
MLFLOW_TRACKING_URI=https://dagshub.com/rafeekalas.official/NewEndtoEndMLProjectMLFlow.mlflow \
MLFLOW_TRACKING_USERNAME=rafeekalas.official \
MLFLOW_TRACKING_PASSWORD=7b0b4dfcf8543980ce201da778225177478e01a0 \
python script.py