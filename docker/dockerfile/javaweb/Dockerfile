FROM tomcat:9.0

MAINTAINER chenjunxi1<chenjunxi1@xxx>

# 进入 Tomcat 部署目录
WORKDIR /usr/local/tomcat/webapps

# 定义参数
ARG JAR_FILE

# 将 war 包拷贝到 tomcat 中，并且改名为 ROOT
COPY ${JAR_FILE} ROOT.war

# 回到 Tomcat 根目录
WORKDIR /usr/local/tomcat/

# 启动时运行命令
CMD bin/catalina.sh run
