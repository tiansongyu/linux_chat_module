# 运行
make
insmod globalvar.ko
gcc read.c -o read
gcc write.c -o write
/read
./write
