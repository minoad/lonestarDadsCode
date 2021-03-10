# Python 3.9 setup

## Ubuntu 20.04

Testing method to generate: Docker

```shell
docker pull ubuntu:focal
docker images
docker run --name testSetupUbuntu20 --interactive --tty  --detach ubuntu:focal /bin/bash
docker exec -it testSetupUbuntu20 /bin/bash
apt update
apt install -y vim tree curl
vim /etc/apt/sources.list
# uncomment deb http://archive.canonical.com/ubuntu focal partner
apt update; apt -y upgrade;
```

Now for the python 3.9 installation

```shell
## Install Python
apt install -y software-properties-common python3.9
alias python=python3.9
echo "alias python=python3.9" >> ~/.bashrc
echo $(which python)
echo $(python --version)

## Install pip
curl -k https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python3.9 get-pip.py
echo $(which pip)
echo $(pip --version)

echo $(which pip3)
echo $(pip3 --version)

echo $(which pip3.9)
echo $(pip3.9 --version)

## Install required modules
pip install virtualenv jupyter jupyter-nbextesion pandas numpy matplotlib
```
