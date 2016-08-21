运行前请做好配置

1. config.properties

temp 指定一个临时文件夹

pic_dir 指定一个图片存放路径

port 指定程序运行端口
http_url 获得平台参数webservice接口地址



2. log4j.properties

log4j.rootLogger=DEBUG,CONSOLE,FILE 测试时可以这样配置

log4j.rootLogger=ERROR,FILE 上线后这样配置
log4j.appender.FILE.File指定一个记录日志的文件


运行start.bat启动

请不要关闭窗口