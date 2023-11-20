# CRC_Cracker
自动读取爆破加密zip/7z/rar中所有1-4字节文件CRC，按顺序输出，参照项目
<br /> https://github.com/playGitboy/zipCrcCracker <br />
https://github.com/theonlypwner/crc32

## 区别
网上zip文件crc爆破代码很多，这个脚本主要区别是不需要手动提取逐个填入CRC值，程序批量从加密的各种压缩包中读取CRC并爆破输出明文

## 应用场景
目前适用类型:zip/7z/~~rar~~，理论上7z能看的都能看    

经测试，rar文件进行加密之后，CRC值似乎进行了加密，所以暂时无法对加密的rar文件进行crc爆破  
正在学习加密算法，别急

## 使用方法
```
crc32.exe <path_to_zip_archive>
```
另外会在当前目录下生成一个output.txt,包含所有可能的flag

## 工具目前存在的小问题(待修复)
~~文件输出排序有问题，如输出排序为[1.txt,10.txt,11.txt,2.txt,20.txt,3.txt]~~  
欢迎提出问题

