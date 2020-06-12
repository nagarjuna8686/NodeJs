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

sudo npm i dotenv bcryptjs jsonwebtoken @hapi/joi

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
