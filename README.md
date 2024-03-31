# mlops-mlflow-project

MLProject: Packaging format for reproducable ML Runs
for python virtualenv we need an env to run. for that

-> create virtual env
-> install all required packages
-> mlflow run --env-manager=local https://github.com/nsd8888/mlops-mlflow-project -P alpha=0.2
-> mlflow models serve --model-uri runs:/f65a54a8957743b8978b09ebe077ecb3/model -p 5050 --no-conda
