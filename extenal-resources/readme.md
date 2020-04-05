- DDD初始化过程遇到的问题

~~~
# 初始化项目时需要另外下载资源包
mvn install:install-file -DgroupId=com.oracle.jdbc -DartifactId=ojdbc6 -Dversion=11.2.0.3 -Dpackaging=jar -Dfile=ojdbc6.jar
mvn install:install-file -DgroupId=com.dawn -DartifactId=java-memcached -Dversion=2.6.6 -Dpackaging=jar -Dfile=java_memcached-release_2.6.6.jar
mvn install:install-file -DgroupId=proxool -DartifactId=proxool -Dpackaging=jar -Dversion=0.9.1 -Dfile=proxool-0.9.1.jar
mvn install:install-file -DgroupId=proxool -DartifactId=proxool-cglib -Dpackaging=jar -Dversion=0.9.1 -Dfile=proxool-cglib.jar
~~~
