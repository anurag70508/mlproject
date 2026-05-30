## End to End Data Science Project

import dagshub
dagshub.init(repo_owner='anurag70508', repo_name='mlproject', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)

MLFLOW_TRACKING_URI=https://dagshub.com/anurag70508/mlproject.mlflow \
MLFLOW_TRACKING_PASSWORD=fd77f238608e3b03f1f9982d47fd75bcd2d95ec7 \
MLFLOW_TRACKING_USERNAME=anurag70508 \
