Dockarize React-App

Step1
git clone https://github.com/Himanshuu03/Docker-Project

step2
cd Dockar-Project

step3
#create dockar image
dockar build -t himanshuu03/crypto-react-app .

step4
#run it on server
dockar run -p 3000:3000 himanshuu03/crypto-react-app
or
dockar run -publish 3000:3000 himanshuu03/crypto-react-app

