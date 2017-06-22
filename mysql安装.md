# MySQL的安装过程  
## 安装过程
1.vim .vimrc 删除第18行就可以复制粘贴文本  
2.用vim打开源列表文件    
sudo vim /etc/apt/sources.list    
3.复制源码  
deb http://mirrors.aliyun.com/ubuntu/ xenial main restricted universe multiverse  
deb http://mirrors.aliyun.com/ubuntu/ xenial-security main restricted universe multiverse  
deb http://mirrors.aliyun.com/ubuntu/ xenial-updates main restricted universe multiverse  
deb http://mirrors.aliyun.com/ubuntu/ xenial-backports main restricted universe multiverse    
#### 测试版源  
deb http://mirrors.aliyun.com/ubuntu/ xenial-proposed main restricted universe multiverse  
