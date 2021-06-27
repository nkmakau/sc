#Safaricom Service Charter Website
This will carry all information on the Service charter. 
Its running on MYSQL 8.0 and Joomla 3.9

The site will be on minikube locally. thus make sure you have the following installed.

virtualbox
minikube
kubectl
favorite editor

#RUNS TO DO:

1. $ kubectl apply -f secrets.yml
output: secret/mysql-pass created

2. $ kubectl apply -f sc_mysql.yaml
3. $ kubectly apply -f sc_front.yaml

4. $ minikube dashboard

5. $ minikube service sc --url

#Author
Noah Makau.