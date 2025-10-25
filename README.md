## Data Science Project

import dagshub
dagshub.init(repo_owner='manishapunj24-png', repo_name='MLproject', mlflow=True)

import mlflow
with mlflow.start_run():
mlflow.log_param('parameter name', 'value')
mlflow.log_metric('metric name', 1)
