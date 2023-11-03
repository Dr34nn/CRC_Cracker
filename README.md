# CRC_Cracker
自动读取爆破加密zip/7z/rar中所有1-4字节文件CRC，按顺序输出，参照项目
https://github.com/playGitboy/zipCrcCracker
https://github.com/theonlypwner/crc32

# 区别
网上zip文件crc爆破代码很多，这个脚本主要区别是不需要手动提取逐个填入CRC值，程序批量从加密的各种压缩包中读取CRC并爆破输出明文

# 应用场景
目前适用类型:zip/7z/rar，理论上7z能看的都能看

# 使用方法
```
main.exe <path_to_zip_archive>
```


