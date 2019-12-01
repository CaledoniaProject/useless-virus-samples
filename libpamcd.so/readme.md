## 说明

当目标程序使用 fopen 读取 /proc 下的文件，使用 tmpfile 构造一个新的文件，并返回 stream。
e.g 过滤 /proc/net/tcp、/proc/stat 等等。值得注意的是，这个样本的CPU利用率是写死的2核
