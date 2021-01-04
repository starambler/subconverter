
[中文文档](https://github.com/tindy2013/subconverter/blob/master/README-cn.md)

docker安装

docker run -d --restart=always -p 25500:25500 tindy2013/subconverter:latest

简单用法：将订阅转clash并排除香港节点另存为myclash.yaml文件

http://127.0.0.1:25500/sub?target=clash&url=sub_url&exclude=HK&filename=myclash.yaml
