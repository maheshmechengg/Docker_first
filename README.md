creat environment
```bash
conda create -n docker python==3.7.0
```

activate env
```bash
conda activate docker
```

Install docker
```bash
sudo apt-get update
sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg \
    lsb-release
```

Check docker installed
```bash
docker run hello-world
```

Get files from github
```bash
git clone https://github.com/maheshmechengg/Docker_first.git
```

Go to dir
```bash
cd Docker_first
```

Install requirements
```bash
pip install -r requirements.txt
```

Run & check app
```bash
python app.py
```

Build docker file
```bash
docker build -t banknote_api .
```

run docker file
```bash
docker run --publish 5000:5000 banknote_api
```

Open another terminal & check if docker is running: will list all running dockers
```bash
docker ps
```
Get ip address
```bash
ifconfig
```

Get this app on another device
```bash
http://<IPAdd>:5000/apidocs
```
If useful, like share, star it & follow
Have fun!!!

