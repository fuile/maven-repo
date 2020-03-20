# maven-repo
maven repository

# pom.xml
```xml
    <repositories>
        <repository>
            <id>maven-repo</id>
            <url>https://github.com/fuile/maven-repo/master</url>
            <snapshots>
                <enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
            </snapshots>
        </repository>
    </repositories>

    <dependencies>

        <dependency>
            <groupId>com.cmsenframework.springboot</groupId>
            <artifactId>cmsen-springboot-common</artifactId>
            <version>1.0.0</version>
        </dependency>
        
        <dependency>
            <groupId>com.cmsenframework.springboot</groupId>
            <artifactId>cmsen-springboot-quartz</artifactId>
            <version>1.0.0</version>
        </dependency>
    </dependencies>
```
