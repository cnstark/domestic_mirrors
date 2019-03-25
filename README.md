# domestic_mirrors

国内镜像源配置文件

## Docker Use

### ubuntu

Add the following code into your Dockerfile.

```shell
# ubuntu16.04
ADD https://raw.githubusercontent.com/yuhao-w/domestic_mirrors/master/ubuntu/ustc-ubuntu1604-sources.list /etc/apt/sources.list
# ubuntu18.04
ADD https://raw.githubusercontent.com/yuhao-w/domestic_mirrors/master/ubuntu/ustc-ubuntu1804-sources.list /etc/apt/sources.list
```

