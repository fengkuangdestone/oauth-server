FROM registry.cn-hangzhou.aliyuncs.com/choerodon-tools/javabase:0.7.0
COPY app.jar /oauth-server.jar
ENTRYPOINT exec java $JAVA_OPTS  -jar /oauth-server.jar
