Dockerize React-App

Step1
git clone https://github.com/Himanshuu03/Docker-Project

step2

cd Docker-Project

step3

#create docker image

docker build -t himanshuu03/Cryptotracker .

step4

#run it on server

docker run -p 3000:3000 himanshuu03/Cryptotracker
