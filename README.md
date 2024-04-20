# docker-one-click-installation-script
docker一键安装/国内机
```bash
wget -N --no-check-certificate https://hub.gitmirror.com/https://github.com/HPUhushicheng/docker-one-click-installation-script/blob/main/zhumao.sh && chmod 700 ./zhumao.sh && ./zhumao.sh
```
docker一键安装/国外机
```bash
wget -N --no-check-certificate https://github.com/HPUhushicheng/docker-one-click-installation-script/blob/main/zhumao.sh && chmod 700 ./zhumao.sh && ./zhumao.sh
```
instantbox 
几秒钟利用docker创建一个服务器，适合演示
https://github.com/instantbox/instantbox
部署
国内机
```bash
mkdir instantbox && cd instantbox
bash <(curl -sSL https://raw.gitmirror.com/instantbox/instantbox/master/init.sh)
```
国外机
```bash
bash <(curl -sSL https://raw.githubusercontent.com/instantbox/instantbox/master/init.sh)
```
