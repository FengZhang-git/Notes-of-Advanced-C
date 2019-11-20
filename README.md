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
