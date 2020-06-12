Mean_stack_project
apt update
apt install nodejs
apt install npm
nodejs -v
npm -v
curl -sL https://deb.nodesource.com/setup_10.x -o nodesource_setup.sh
bash nodesource_setup.sh
apt install nodejs -y
nodjs -v
nodejs -v
npm -v
apt install build-essential
npm install -g @angular/cli
ng --version

find port:  lsof -i :4200

FrontEnd: port: 4200
start: /project/ng serve --host 0.0.0.0


http://18.218.21.35:4200/

FrontEnd: change ip to current vm ip: vim /root/new_project/src/app/service/api.service.ts
Backend: change ip address to current vm ip: vim /root/new_project/backend/server.js

FrontEnd: npm i
FrontEnd Start: ng serve --host 0.0.0.0 (port: 4200)


Backend: sudo npm i dotenv bcryptjs jsonwebtoken @hapi/joi 
Backend Start: sudo npm run start (port: 4000)

Api's:
Register Api:  http://localhost:4000/api/user/register

http://18.218.21.35:4000/api/user/register
body: raw-->json
{
        "name":"Nagarjuna",
	"email":"nagarjuna@infosys.com",
	"password":"Infosys@123"
}

mongodb+srv://employeedb:xymiOFTBtmUdFpJi@cluster0-4epwd.mongodb.net/employeedb?retryWrites=true&w=majority


RHEL:

    1  yum install -y gcc-c++ make
    2  curl -sL https://rpm.nodesource.com/setup_12.x | sudo -E bash -
    3       sudo yum install yarn
    4  sudo yum install nodejs
    5  node -v
    6  npm -v
    7  npm install -g @angular/cli
    8  ng -version
    9  ng --version
   10  cler
   11  clear
   12  git clone https://github.com/nagarjuna8686/NodeJs.git
   13  yum install git
   14  git clone https://github.com/nagarjuna8686/NodeJs.git
   15  sudo chmod 777 -R NodeJs/
   16  cd NodeJs/
   17  vim src/app/service/api.service.ts
   18  vi src/app/service/api.service.ts
   19  cd backend/
   20  vi server.js
   21  npm i dotenv bcryptjs jsonwebtoken @hapi/joi
   22  npm audit fix
   23  npm audit fix --force
   24  npm fund
   25  npm install appdynamics@20.4.2
   26  npm install appdynamics@4.5.21
   27  npm install appdynamics@20.5.0
   28  npm install appdynamics@20.5.0 --force
   29  npm audit fix
   30  vi server.js
