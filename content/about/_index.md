---
title: "关于lank8s"
description: "github.com/liangyuanpeng"
author_image : "images/liangyuanpeng.png"
author_signature : ""
draft: false
---

在国内需要想尽办法拉取K8S镜像,原本有微软国内代理节点gcr.azk8s.cn,但其在2020年4月初已经关闭公开访问,只有使用了微软云的国内机器才可使用,这实在是很可惜,因为我之前就是使用的gcr.azk8s.cn.也有很多人搭建了自己的k8s镜像同步的东西,这让我想到了不要重复造轮子这句话.因为我创建了lank8s,计划长期免费提供K8S镜像拉取服务.当前仅支持K8S部署的基本镜像,其他gcr镜像无法提供,因为lank8s也是将数据存储在阿里云镜像库,并不是一个真正意义上的docker仓库.  

lank8s当前服务器配置并不高,当无法拉取镜像时请稍等一下再尝试拉取镜像.