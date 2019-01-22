# Dependancies
* Kubernetes
* Kubernetes cluster (eg. minikube)
* Helm

# Steps
```
git clone https://github.com/kanuahs/flask-sample-chart.git

helm init

helm install flask-sample-chart --name=test1

helm status test1
```
* go to "testhost" in browser
# Note
* To enable ingress with minikube
```
minikube addons enable ingress
```
* Add this line to /etc/hosts
```
192.168.99.100 testhost
```
