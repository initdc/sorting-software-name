# [排序软件包名](https://github.com/initdc/sorting-software-name)
> 解决写脚本时的格式化问题

## 起因

买了两个开发板, 准备学习嵌入式, 而构建系统镜像需要复杂的操作
裸机系统安装软件包未免太过难以管理 溯源 回滚. 想来Docker还是
最好的方案.

## 排序方法

JavaScript [Array.prototype.sort()](https://mdn1.moz.one/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)


## 运行实例

https://build.moz.one


## 示例

```sh
# 80 char
asciidoc autoconf autotools-dev bash bc binutils build-essential bzip2 cpio curl  \
cvs dblatex device-tree-compiler g++ gcc gcc-aarch64-linux-gnu  \
gcc-arm-linux-gnueabihf genext2fs git gitk graphviz gzip intltool libdrm-dev  \
libglade2-dev libglib2.0-dev libgtk2.0-dev libncurses5 libsigsegv2 libssl-dev  \
libudev-dev libusb-1.0-0-dev m4 make mercurial mtools openssh-client parted  \
patch perl python rsync sed subversion tar texinfo u-boot-tools unzip w3m wget  

# 5 name
asciidoc autoconf autotools-dev bash bc \
binutils build-essential bzip2 cpio curl \
cvs dblatex device-tree-compiler g++ gcc \
gcc-aarch64-linux-gnu gcc-arm-linux-gnueabihf genext2fs git gitk \
graphviz gzip intltool libdrm-dev libglade2-dev \
libglib2.0-dev libgtk2.0-dev libncurses5 libsigsegv2 libssl-dev \
libudev-dev libusb-1.0-0-dev m4 make mercurial \
mtools openssh-client parted patch perl \
python rsync sed subversion tar \
texinfo u-boot-tools unzip w3m wget 
```

## 贡献

欢迎发现问题, 提出改进

## 许可证

MIT
