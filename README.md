# mlflow-basic-operation

import dagshub
dagshub.init(repo_owner='irene-Datalover', repo_name='mlflow-basic-operation', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)