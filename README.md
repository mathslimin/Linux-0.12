# Linux-0.12
Linux0.12内核代码中文注释 + 在高版本GCC 5.4.0 + Ubuntu 16.04

编译结果如下:

![image](https://github.com/sky-big/Linux-0.12/blob/master/compile_picture.jpg)


运行结果如下:

![image](https://github.com/sky-big/Linux-0.12/blob/master/run_result.jpg)

运行环境下载地址:
http://oldlinux.org/Linux.old/bochs/linux-0.12-080324.zip

### 运行方法
```shell
sudo apt-get install bin86
make all
#qemu 图形化运行
qemu-system-i386 -m 32M -boot a -fda Kernel_Image -fdb rootimage-0.12-fd -hda rootimage-0.12-hd 
```
