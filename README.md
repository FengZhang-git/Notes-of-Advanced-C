# 高级C学习笔记1
## daytimetcpser.c & daytimetcpcli.c

> 1.Execute the following from the src/ directory:

    ./configure    # try to figure out all implementation differences

    cd lib         # build the basic library that all programs need
    make           # use "gmake" everywhere on BSD/OS systems

    cd ../libfree  # continue building the basic library
    make

    cd ../libroute # only if your system supports 4.4BSD style routing sockets
    make           # only if your system supports 4.4BSD style routing sockets

    cd ../libxti   # only if your system supports XTI
    make           # only if your system supports XTI

    cd ../intro    # build and test a basic client program
    make
>2.Execute :(enter intro)<br>
```java
    sudo ./daytimetcpser
```
>3. Execute:<br>
```java
    sudo ./daytimetcpcil 127.0.0.1
```
## 2019.12.5
>1.ctags:<br>
```java
    ctags -R *:生成ctags
    less tags: 执行一下，看看生成的tags
    :set tags+=../tags
    :set tags+=/usr/include/tags
```
>2.note:<br>
```java
ls -lrt :list 倒序 time
echo server/client: say hello
INSERT
REPLACE
//查找shift+*：往后找
shift+# ：往前找
/cli 找到 单击 n:next shift+n 往前找
选中y，p粘贴，删除dd,删除且保留空行shift+d
替换：
:%s/servaddr/as
unpv13e: uctags -R .
R(Recurisive)
cd /usr/include
cd ~
ls
vim .vimrc
ctrl+w+n:
ctrl+w+v:
ctrl+w+向上
fd :file discriptor 文件描述符
:tselect   选择自己要读的那个函数定义


```
