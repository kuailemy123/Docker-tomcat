### Tomcat
---

以 Alpine Linux image为基础镜像构建tomcat, java为oracle jdk。


### 版本
---

- `v7.0.86-jdk8` (docker tags: `v7.0.86-jdk8`) : tomcat版本为`7.0.86`, OracleJDK 版本为 `8.131.11`
- `v8.0.52-jdk8` (docker tags: `v8.0.52-jdk8`, latest) : tomcat版本为`8.0.52`, OracleJDK 版本为 `8.131.11`


### 使用
---
```
docker run -it --rm -p 8888:8080 lework/tomcat:v8.0.52-jdk8
```