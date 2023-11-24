# Command
## Ubuntu Win10子系统


nano ~/.bash_profile 修改配置文件 <br>


echo "cd /mnt/d/mygo/src" >> ~/.bash_profile  设置默认打开路径<br>

C:\Users\imlau\AppData\Local\Microsoft\WindowsApps\Ubuntu 安装位置<br>

ubuntu1804.exe  config --default-user root  执行默认root登录<br>


## Windows
netstat -ano | findstr :8080 查看该端口号的进程ID <br>
tasklist /fi "PID eq 13132" 查看进程的内存使用情况<br>
嘻嘻嘻嘻嘻嘻嘻嘻嘻嘻嘻嘻嘻嘻嘻嘻嘻嘻嘻

ubuntu配置Go环境<br>
sudo tar -C /usr/local -xzf go1.20.11.linux-amd64.tar.gz<br>
sudo vim /etc/profile<br>
export GOROOT=/usr/local/go # 表示源码包路径<br>
export GOPATH=$HOME/go # 将go的编译环境添加到path中<br>
export PATH=$PATH:$GOROOT/bin:GOPATH/bin # 开发者go的项目默认路径<br>
source /etc/profile<br>
go version<br>
