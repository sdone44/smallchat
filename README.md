# 端口
服务端默认端口是7771
修改重新编译成自己想要的端口
#define SERVER_PORT 7711

# 编译
gcc -o smallchat smallchat.c

# 运行服务
./smallchat

# 连接服务
telnet 127.0.0.1 7711

