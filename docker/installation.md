### 在deepin 15.4.1安装docker

这个博客说的简明易懂：https://blog.choldrim.com/2016/04/10/docker%E5%9C%A8deepin%E7%9A%84%E5%AE%89%E8%A3%85/

需要注意的是deepin 15.4.1使用stretch(debian 9)的源

```
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/debian stretch stable"
```

### 使用中科大的docker hub mirror

http://mirrors.ustc.edu.cn/help/dockerhub.html

### 设置docker image的位置/迁移镜像

这个用软连接的方法有效，虽然比较脏。。。
https://forums.docker.com/t/how-do-i-change-the-docker-image-installation-directory/1169
