# kubernetes
Just a few tweaks and learns for gke.

kubectl create secret generic cloudsql-instance-credentials --from-file=credentials.json=service_account.json

kubectl create secret generic cloudsql-db-credentials --from-literal=username=root --from-literal=password=root_password_db
