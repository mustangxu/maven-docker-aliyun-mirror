# A maven docker image with aliyun mirror configed
This image is based on maven:3.9-eclipse-temurin-23 with a pre-configed `~/.m2/settings.xml` file:
```
<settings>
    <mirrors>
        <mirror>
            <id>alimaven</id>
            <name>aliyun maven</name>
            <url>https://maven.aliyun.com/nexus/content/groups/public/</url>
            <mirrorOf>central</mirrorOf>
        </mirror>
    </mirrors>
</settings>
```
