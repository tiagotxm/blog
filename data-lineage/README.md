
helm install openmetadata-dependencies open-metadata/openmetadata-dependencies --set airflow.scheduler.logCleanup.enabled=false --values data-lineage/helm/openmetadata-dependencies/values.yaml 

helm install openmetadata open-metadata/openmetadata


