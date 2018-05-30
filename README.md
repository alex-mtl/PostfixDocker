# PostfixDocker
Postfix Mysql Dovecot Docker

docker build .

docker run -d --name postfix -p 143:143 -p 25:25 -p 993:993 -p 3306:3306 umise:pmd

