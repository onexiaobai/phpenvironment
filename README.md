# phpenvironment 
## Reason 
* vagrant下PHP环境的box文件网上资源较少且版本比较低，PHP7以上的我是没找到

* MACOS系统PHP集成环境不如windows下的使用起来方便(简单吐槽一下)
    
   * MAMP是收费的，而且比较贵，
   * XAMPP对于MACOS高版本系统兼容做的不好， 且缺少常用到的memcache和redis
   * 大多数人会选择使用brew，安装成本以及使用成本比较大，所用到的需要一个一个进行安装配置，而且日后更新不方便

## Introduction
* 用于vagrant下的一套完整的PHP开发环境box文件，box文件系统为centos7,包含PHP7.1、mysql5.5、nginx1.14、memcached1.5、redis4.0


