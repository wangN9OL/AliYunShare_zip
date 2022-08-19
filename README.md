# AliYunShare_zip
阿里云zip文件不能分享解决办法


阿里云盘最近分享一些文件给朋友发现zip文件不能分享，官方暂且也未表示什么时候会支持，所以我们只能先用一点黑科技

macOS用户可以这样操作：

    将压缩好的zip和一张jpg（其他格式可以自己尝试）放在同一个文件夹下，使用cat命令合并伪装成jpg文件 
   `cat filename1 filename2 > newfile.jpg`
   
    解压缩：通过unzip命令解压缩，在目录下使用命令
    
   `unzip -n newfile.jpg`


windows用户可以参考:https://github.com/smloli/AlizipShare

