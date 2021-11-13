# Ubuntu Remote Desktop Docker環境

# Requirement
* [docker](https://www.docker.com/)

# Install
Docker起動
```
docker-compose up -d --build
```

コンテナに入る
```
docker exec -it ubuntu-desktop-lxde-vnc bash
```

# Usage

作業フォルダ：```./src```

リモートデスクトップに接続
http://127.0.0.1:6080/

# Note
* [dorowu/ubuntu-desktop-lxde-vnc](https://hub.docker.com/r/dorowu/ubuntu-desktop-lxde-vnc/) 

# Author
* [こぴぺたん](https://twitter.com/c_a_p_engineer)

# License
[MIT license](https://en.wikipedia.org/wiki/MIT_License).
