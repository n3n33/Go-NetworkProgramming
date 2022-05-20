## GO 설치 - Linux OS
```
wget https://go.dev/dl/go1.18.2.linux-amd64.tar.gz
tar xvzf go1.18.2.linux-amd64.tar.gz

vi /etc/profile.d/go_home.sh
export GO_HOME=/opt/go
PATH=$PATH:$GO_HOME/bin


```