# docker_dst_server

docker img owner is -> https://hub.docker.com/r/webhippie/dst

Prerequisites
Linux x86_64 and runs Docker (18.05.0-ce or later).
You may need a public IP to make your server accessable from Internet.
You need 4 UDP ports exposed to the public network. (See FAQ for details.)
CPU: 1 core is somewhat enough for a small-scale server (but don't try 60 ticks, start from 15 or 30).
Memory: We recommend reserving 1GiB Memory for the server, plus 60MiB per active user.
Disk size: the Docker image takes 1.5GiB, and you need at least another 5MiB for maps, configs and logs. 4GiB available disk space is recommended.

4人 1.5G 内存
客户端连接很卡:
1. ticks 过高
1. 服务器端使用了高刷新率地图插件