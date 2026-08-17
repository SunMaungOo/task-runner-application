# Overview 

# Create Secret value for task-runner-authdb

```
kubectl create secret generic auth-mongodb -n task-runner \
  --from-literal=MONGO_INITDB_ROOT_USERNAME='<mongodb-user>' \
  --from-literal=MONGO_INITDB_ROOT_PASSWORD='<mongodb-password>'
```
