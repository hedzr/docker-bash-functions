# docker-functions

## Installation


```bash
wget -O ~/.bashrc_docker -c /data/docker-work/docker-functions
#cp /data/docker-work/docker-functions ~/.bashrc_docker
echo "[ -f ~/.bashrc_docker ] && . ~/.bashrc_docker" >> ~/.bashrc; source ~/.bashrc
```

## Usages

参考了 <https://github.com/yeasy/docker_practice/raw/master/_local/.bashrc_docker>

运行：

docker-run-daemon
docker-run-it

停止：

docker-stop
docker-stop-all

从运行列表中移除：

docker-kill-all
docker-rm-all
docker-rm

