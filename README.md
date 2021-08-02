# Dockers
```bash
mkdir docker
cd docker
```

install virtualenv
```bash
pip install virtualenv
virtualenv "docker"
```

Activate env
```bash
source docker/bin/activate
```

check docker env
```bash
docker hello-world
```

check docker version
```bash
docker --version
```

Make docker file

```bash
FROM continuumio/anaconda3:4.4.0
COPY . /usr/app/
EXPOSE 5000
WORKDIR /usr/app/
RUN pip install -r requirements.txt
CMD python flask_api.py
```

Run below commands on docker
```bash
docker build -t monet_apt .
```

see dockers
```bash
docker ps
```

Running the docker
```bash
docker run -p 8000:8000 money_api
```



















