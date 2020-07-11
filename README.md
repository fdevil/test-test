[TOC]



# Linux学习汇总

## 1、python+sphinx+github+readthedocs

```
//安装sphinx主题  -i 临时使用清华大学的镜像源
pip install sphinx_rtd_theme -i https://pypi.tuna.tsinghua.edu.cn/simple/ 
```





## 2、git安装及连接github

我本地的git配置的多账号，切换的时候需要使用ssh-add ~/.ssh/id_rsa_name这个命令，今天运行的时候出现Could not open a connection to your authentication agent.

启动ssh代理并添加密钥
首先，如果想要使用ssh代理，我们则需要先启动ssh代理，也就是启动ssh-agent程序，如下两条命令都可以启动代理，但是略有不同。

ssh-agent $SHELL

eval `ssh-agent`
这时可以使用：ssh-agent bash 命令，然后再次使用ssh-add ~/.ssh/id_rsa_name这个命令就没问题了。

````
ssh-keygen –t rsa –C "fdevilpublic@163.com"
ssh –T git@github.com
ssh-agent bash
ssh-add ~/.ssh/id_rsa
````




## 2、git安装及连接github

链接上了


