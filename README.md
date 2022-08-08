# Dockerize React-App

## Step1 - Clone the repository

```
 git clone https://github.com/Himanshuu03/Docker-Project
```

## Step2 - Change directory to Docker-project

```
 cd Docker-Project
```

## Step3 - Create docker image

```
docker build -t himanshuu03/Cryptotracker .
```

## Step4 - Run it on server

```
 docker run -p 3000:3000 himanshuu03/Cryptotracker
```
