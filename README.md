como ejecuta la app

npm i / npm install
node app.js

1. crear una EC2 en AWS 
2 Crear una IP elastica
3. Asociar la IP Elastica hacia la EC2
4. conectarnos a la EC2 con la key.pem
5. sudo apt update
6. sudo apt upgrade
7. sudo apt install -y git htop wget
8. instalar node / wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

8. ejecutar estos comandos
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion

9. nvm --version
10.  nvm install --lts
11. node --version / npm -v
12. cd /home/ubuntu/
13. ssh-keygen  (enter a todo)
13. git clone git@github.com:jrojasde/demo-lab-utec.git
14. ubicar el ssh cd /home/ubuntu/.ssh/
15. cat id_rsa.pub  copiar en SSH configuracion en GitHub
16. clonar en el lugar deseado 
git clone **********
17. npm install
18. node app.js
19. crear ruta hacia el puerto 3000 en los "grupos de seguridad" en AWS
20. npm install -g pm2
21. npm install -g pm2
22. pm2 start (codigo de app) --name=(nombre de la app)
23. pm2 save
24. pm2 startup
25. sudo env PATH=$PATH:/home/ubuntu/.nvm/versions/node/v18.17.1/bin /home/ubuntu/.nvm/versions/node/v18.17.1/lib/node_modules/pm2/bin/pm2 startup systemd -u ubuntu --hp /home/ubuntu
