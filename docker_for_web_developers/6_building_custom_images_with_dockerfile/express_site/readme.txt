1.创建
docker image build -t doerlee/node .

2.运行
docker container run -d --name node_web -p 8080:3000 doerlee/node