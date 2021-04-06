Ubuntu 16 Xenial

```
apt update -y
apt install -y \
wget \
build-essential \
libssl-dev \
zlib1g-dev \
libbz2-dev \
libreadline-dev \
libsqlite3-dev \
libncurses5-dev \
libncursesw5-dev \
xz-utils \
tk-dev
```

Download and Install : Python Source Code Gzipped source tarball
```
dpkg --configure -a
cd /usr/src
wget https://www.python.org/ftp/python/3.9.4/Python-3.9.4.tgz
tar xf Python-3.9.4.tgz
cd Python-3.9.4
./configure --enable-optimizations
make altinstall

sudo pip3.9 install --upgrade pip
```
