# Setup
kubectl create secret generic mysql --from-literal=password=mysql123
kubectl apply -f volumes.yml 
kubectl apply -f mysql-deployment.yml 
kubectl apply -f drupal-deployment.yml 
