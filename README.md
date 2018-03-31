# fork fome https://moeclub.org/2017/03/25/82/
`wget --no-check-certificate -qO DebianNET.sh 'https://raw.githubusercontent.com/yanshibin/Debian-Ubuntu-REINSTALL/master/DebianNET.sh' && chmod -x DebianNET.sh && bash DebianNET.sh -d jessie -v amd64`  

| 使用: | 安装Debian 7                        |  安装Debian 8                            |安装Debian 9|
| :-----|:----------------------------------:| :---------------------------------------:|:------------------:|
| x32   |bash DebianNET.sh -d wheezy -v i386  | bash DebianNET.sh -d jessie -v i386 |bash DebianNET.sh -d stretch -v i386|
| x64   |bash DebianNET.sh -d wheezy -v amd64 | bash DebianNET.sh -d jessie -v amd64 |bash DebianNET.sh -d stretch -v amd64|

|  使用: | 安装Ubuntu 14.04                        |  安装Ubuntu 16.04                           |安装Ubuntu 17.04|
| :-----|:----------------------------------:| :---------------------------------------:|:------------------:|
| x32   |bash DebianNET.sh -d trusty -v 32 | bash DebianNET.sh -d xenial -v 32 |bash DebianNET.sh -d zesty -v 32|
| x64   |bash DebianNET.sh -d trusty -v 64 | bash DebianNET.sh -d xenial -v 64 |bash DebianNET.sh -d zesty -v 64|




                                  
### 确保安装了所需软件:
```Debian/Ubuntu: apt-get install -y gawk sed grep```  
```RedHat/CentOS: yum install -y gawk sed grep```  
### 如果出现了错误,请运行:  
```Debian/Ubuntu: apt-get update```  
```RedHat/CentOS: yum update```  
