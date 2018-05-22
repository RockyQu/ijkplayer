# ijkplayer
基于 [Bilibili](https://github.com/Bilibili) 开源播放器 [ijkplayer 0.8.8](https://github.com/Bilibili/ijkplayer) 编译的完整项目

# Build

install software

```
sudo apt-get update
sudo apt-get install git
sudo apt-get install yasm
```

Clone ijkplayer

```
git clone https://github.com/Bilibili/ijkplayer.git ijkplayer-android
```

Init
```
./init-android.sh
```

Support Https
```
./init-android-openssl.sh
```

Build openssl
```
./compile-openssl.sh clean
./compile-openssl.sh all
```

Build ffmpeg
```
./compile-ffmpeg.sh clean
./compile-ffmpeg.sh all
```

Get ijkplayer
```
./compile-ijk.sh all
```

# 详细教程
[使用 Ubuntu 编译 ijkplayer 源码](http://rockycoder.cn/ijkplayer/2018/04/18/Compile-ijkplayer.html)
