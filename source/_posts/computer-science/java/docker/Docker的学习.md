---
title: Docker的学习
date: 2024-09-14 00:49:40
categories:
  - [计算机科学, Java, Docker]
tags:
  - 后端
---

# Docker的指令

## docker的基本指令

| **命令**       | **说明**                       |                         **文档地址**                         |
| :------------- | :----------------------------- | :----------------------------------------------------------: |
| docker pull    | 拉取镜像                       | [docker pull](https://docs.docker.com/engine/reference/commandline/pull/) |
| docker push    | 推送镜像到DockerRegistry       | [docker push](https://docs.docker.com/engine/reference/commandline/push/) |
| docker images  | 查看本地镜像                   | [docker images](https://docs.docker.com/engine/reference/commandline/images/) |
| docker rmi     | 删除本地镜像                   | [docker rmi](https://docs.docker.com/engine/reference/commandline/rmi/) |
| docker run     | 创建并运行容器（不能重复创建） | [docker run](https://docs.docker.com/engine/reference/commandline/run/) |
| docker stop    | 停止指定容器                   | [docker stop](https://docs.docker.com/engine/reference/commandline/stop/) |
| docker start   | 启动指定容器                   | [docker start](https://docs.docker.com/engine/reference/commandline/start/) |
| docker restart | 重新启动容器                   | [docker restart](https://docs.docker.com/engine/reference/commandline/restart/) |
| docker rm      | 删除指定容器                   | [docs.docker.com](https://docs.docker.com/engine/reference/commandline/rm/) |
| docker ps      | 查看容器                       | [docker ps](https://docs.docker.com/engine/reference/commandline/ps/) |
| docker logs    | 查看容器运行日志               | [docker logs](https://docs.docker.com/engine/reference/commandline/logs/) |
| docker exec    | 进入容器                       | [docker exec](https://docs.docker.com/engine/reference/commandline/exec/) |
| docker save    | 保存镜像到本地压缩文件         | [docker save](https://docs.docker.com/engine/reference/commandline/save/) |
| docker load    | 加载本地压缩文件到镜像         | [docker load](https://docs.docker.com/engine/reference/commandline/load/) |
| docker inspect | 查看容器详细信息               | [docker inspect](https://docs.docker.com/engine/reference/commandline/inspect/) |

## docker的数据卷指令

| **命令**              | **说明**             |                         **文档地址**                         |
| :-------------------- | :------------------- | :----------------------------------------------------------: |
| docker volume create  | 创建数据卷           | [docker volume create](https://docs.docker.com/engine/reference/commandline/volume_create/) |
| docker volume ls      | 查看所有数据卷       | [docs.docker.com](https://docs.docker.com/engine/reference/commandline/volume_ls/) |
| docker volume rm      | 删除指定数据卷       | [docs.docker.com](https://docs.docker.com/engine/reference/commandline/volume_prune/) |
| docker volume inspect | 查看某个数据卷的详情 | [docs.docker.com](https://docs.docker.com/engine/reference/commandline/volume_inspect/) |
| docker volume prune   | 清除数据卷           | [docker volume prune](https://docs.docker.com/engine/reference/commandline/volume_prune/) |

## Docker的网络指令

|         **命令**          |         **说明**         |                         **文档地址**                         |
| :-----------------------: | :----------------------: | :----------------------------------------------------------: |
|   docker network create   |       创建一个网络       | [docker network create](https://docs.docker.com/engine/reference/commandline/network_create/) |
|     docker network ls     |       查看所有网络       | [docs.docker.com](https://docs.docker.com/engine/reference/commandline/network_ls/) |
|     docker network rm     |       删除指定网络       | [docs.docker.com](https://docs.docker.com/engine/reference/commandline/network_rm/) |
|   docker network prune    |     清除未使用的网络     | [docs.docker.com](https://docs.docker.com/engine/reference/commandline/network_prune/) |
|  docker network connect   | 使指定容器连接加入某网络 | [docs.docker.com](https://docs.docker.com/engine/reference/commandline/network_connect/) |
| docker network disconnect | 使指定容器连接离开某网络 | [docker network disconnect](https://docs.docker.com/engine/reference/commandline/network_disconnect/) |
|  docker network inspect   |     查看网络详细信息     | [docker network inspect](https://docs.docker.com/engine/reference/commandline/network_inspect/) |
