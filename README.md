# config-repo

####启动服务，使用浏览器访问如下ws接口或使用curl:

http://localhost:8088/config/test

http://localhost:8088/config/test/master

http://localhost:8088/config-dev.yml

http://localhost:8088/master/config-dev.yml

http://localhost:8088/config-pro.properties

http://localhost:8088/master/config-pro.properties

均可看到对应的配置信息，说明服务成功获取到github上的配置。

####使用客户端应用来获取配置。

http://localhost:7002/from   

这个地址可以获取到相应配置文件中设置的对应的文件中的值，eg: git-dev-1.0
