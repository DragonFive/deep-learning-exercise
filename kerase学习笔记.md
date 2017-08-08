---
title: kerasee学习笔记
tags: 新建,模板,小书匠
grammar_cjkRuby: true
---


使用docker安装keras
```
$ docker run -it --rm $(ls /dev/nvidia* | xargs -I{} echo '--device={}') -v /srv/ai:/srv/ai gw000/keras:1.2.0-py3-th-gpu 

```
