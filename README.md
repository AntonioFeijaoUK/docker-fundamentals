# docker-fundamentals
## Docker Fundamentals course

* my raw notes from Acloud.guru docker-fundamentals course
  - https://acloud.guru/course/docker-fundamentals

```bash

docker info

docker run hello-world


docker image build -t web1 .

docker image rm 0781 -f

docker image build -t web1 .


docker container --help

docker container ls

docker container run -it -p 5000:5000 -e FLASK_APP=app.py web1

docker container prune

docker container run -it --rm --name web1_2 -p 5000 -e FLASK_APP=app.py -d web1
docker container run -it --rm --name web1_3 -p 5000 -e FLASK_APP=app.py -d web1

docker container stats

docker container run -it --name web1_3 -p 5000 -e FLASK_APP=app.py -d --restart on-failure web1

docker container logs -f web1_2

docker container stop web1
docker container rm web1
docker container rm shark_pike

docker container logs -f web1






```
