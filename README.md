### Tomcat
---

以 Alpine Linux image为基础镜像构建tomcat, java为oracle jdk。


### 版本
---

- 8.131.11 (docker tags: v8.131.11) : OracleJDK 版本为 8.131.11


### 使用
---
```
docker run -it --rm -p 8888:8080 lework/tomcat:v7.0.86-jdk8
```