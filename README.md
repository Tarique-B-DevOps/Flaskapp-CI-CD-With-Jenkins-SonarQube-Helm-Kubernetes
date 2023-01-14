# Jenkins CI/CD Pipeline for Flask app with SonarQube, Docker and Helm Chart for Kubernetes.


- #### Pipeline Script = [`Jenkinsfile-k8s`](Jenkinsfile-k8s)

- #### Helm Chart = [`helm-chart`](helm-chart)

# Pre-requisites :

- #### Jenkins Controller
- #### Jenkins Slave Node with Kubernetes Env.
- #### Kubernetes Cluster
- #### Helm Chart
- #### SonarQube Integration with Jenkins
- #### Docker Hub Account 
- #### Jenkins Integration with Github


# Architecture

![flask-deployment-architecture](https://user-images.githubusercontent.com/86839948/212464905-2c0fb106-2cda-4404-b9ea-2d27f70c9035.png)

# Screenshots :

- ## Kubernetes Cluster


![Screenshot (50)](https://user-images.githubusercontent.com/86839948/212459979-e0117131-483f-4c5b-a41c-2ba2250c0664.png)


- ## Pipeline


![Screenshot (44)](https://user-images.githubusercontent.com/86839948/212460559-af3b7ad1-49bb-4404-afdd-13e1873df3bb.png)


- ## SonarQube Analysis


![Screenshot (42)](https://user-images.githubusercontent.com/86839948/212460112-4f706aa8-591f-49e9-abbb-cdc812f8c381.png)


- ## DockerHub Repo


![Screenshot (56)](https://user-images.githubusercontent.com/86839948/212460704-9eef2d0f-4bbd-4ec7-9d0e-edbbe89ab699.png)


- ## Kubernetes Resources 


![Screenshot (54)](https://user-images.githubusercontent.com/86839948/212460026-9091caa7-95a6-460c-9128-6b417c639c8e.png)


- ## Access Application on Loadbalancer URL.


![Screenshot (36)](https://user-images.githubusercontent.com/86839948/211161336-531aceaa-021d-4e71-b504-30e2b7383e21.jpg)


