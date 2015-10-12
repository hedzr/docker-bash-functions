# docker-functions

## Installation


```bash
wget -O ~/.bashrc_docker -c https://raw.githubusercontent.com/hedzr/docker-bash-functions/master/docker-functions
#cp /data/docker-work/docker-functions ~/.bashrc_docker
echo "[ -f ~/.bashrc_docker ] && . ~/.bashrc_docker" >> ~/.bashrc; source ~/.bashrc
```

## Usages

参考了 <https://github.com/yeasy/docker_practice/raw/master/_local/.bashrc_docker>

```bash
# 运行：

CID=$(docker-run-daemon <tag>)
docker-run-it <tag>

# 停止：

docker-stop <tag>
docker-stop-all <tag>

# 从运行列表中移除：

docker-kill-all <tag>
docker-rm-all <tag>
docker-rm <tag>

# 获得容器ID

echo $(docker-cid <tag>)

# 获得容器的运行进程ID

echo $(docker-pid <cid>)
echo $(docker-pid $(docker-cid <tag>))

# 获得运行时容器的IP

echo $(docker-ip <cid>)
echo $(docker-ip $(docker-cid <tag>))

```
