# 知识星球数据抓取
本工具用于自动连接到已经付费的知识星球，下载所有的文章。
后续可以跟根据需要过滤一些数据，生成Word文档，方便打印学习。

学习理财、财经知识可以到知识星球搜索“老齐的读书圈”和“齐俊杰的粉丝群”，都很不错。代码中就拿这两个星球做为例子。


有疑问请发邮件至zhm1027@foxmail.com

#group.ini
用于记录每个星球上次下载的时间，避免重复下载数据。

#Zsxq.ini
用于配置知识星球的各种URL，其中版本号更新得会快一些。
DOWNLOAD_FILE_FLAG用于配置是否在下载文章的同时下载对应的文件（如果有的话）。

#headers.txt
该文件用于更新Reqeust Hearder,首先在网页中登录知识星球，然后直接从Network中找到对应的Request，再将Request Hearder复制过来就可以。

