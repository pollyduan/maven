# maven

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


mvn deploy -DaltDeploymentRepository=pollyduan-mvn-repo::default::file:/Users/pollyduan/git/maven/
