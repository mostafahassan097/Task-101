# Task-101


## Steps To Access Thec Cluster and Reading the Content of Secret(Task Details) 
#### Make Sure You have copy from your config file before use the new one 
```
cp ~/.kube/config  ~/.kube/config.bk
- Copy Config to ~/.kube/config
cp config  ~/.kube/config
```
#### Get the Secret and Decode it 
```
kubectl edit secret devops-task 
- Copy the secret than decode it using below command 
echo 'SECRET' | base64 --decode
```
![App Screenshot](https://github.com/mostafahassan097/Task-101/blob/master/images/1.png)
![App Screenshot](https://github.com/mostafahassan097/Task-101/blob/master/images/2.png)

#### 1. install this app ( https://github.com/digitalocean/sample-nodejs )

```
1- Create a Dockerfile for the 
2- build it and push it my docker accout 
docker build -t <dockerhub-username>/<image-name>:<tag> .
docker login
docker push <dockerhub-username>/<image-name>:<tag>
```
#### 2. Install MongoDB 
#### 3. install RabbitsMQ 
#### 4. install RabbitMQ
```
git clone https://github.com/mostafahassan097/Task-101.git
kubectl apply -f ./Task-01
```
![App Screenshot](https://github.com/mostafahassan097/Task-101/blob/master/images/3.png)
