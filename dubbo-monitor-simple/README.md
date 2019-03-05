# dubbo-monitor-simple

## How to use it

You can get a release of dubbo monitor in three steps:

* Step 1:

```
git clone https://github.com/smartbetter/dubbo-ops.git
```

Specify registry address in dubbo-ops/dubbo-monitor-simple/src/main/resources/conf/dubbo.properties

* Step 2:

```
cd dubbo-ops/dubbo-monitor-simple && ./build.bat
```

* Step 3:

Then you will find:

dubbo-monitor-simple-2.0.0-assembly.tar.gz in dubbo-monitor-simple\target directory. Unzip it you will find the shell scripts for starting or stopping monitor.

```
cd target
tar -zxvf dubbo-monitor-simple-2.0.0-assembly.tar.gz
cd dubbo-monitor-simple-2.0.0/assembly.bin
```

start/stop/restart/debug start/system status command:

    ./server.sh start
    ./server.sh stop
    ./server.sh restart
    ./server.sh debug
    ./server.sh dump

Visit http://localhost:7002
