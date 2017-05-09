# maven

在pom中增加仓库
---

pom.xml

```xml
<repositories>
  <repository>
    <id>pollyduan-mvn-repo</id>
    <url>https://raw.github.com/pollyduan/maven/master/</url>
    <snapshots>
      <enabled>true</enabled>
      <updatePolicy>always</updatePolicy>
    </snapshots>
  </repository>
</repositories>
```

增加依赖
---

```xml
<dependency>
  <groupId>com.pollyduan</groupId>
<artifactId>common</artifactId>
  <version>0.0.1-SNAPSHOT</version>
</dependency>
```
