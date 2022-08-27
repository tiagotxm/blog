helm repo add apache-airflow https://airflow.apache.org

helm pull apache-airflow/airflow --untar

helm install airflow -f helms/airflow/values.yaml helms/airflow -n airflow --create-namespace