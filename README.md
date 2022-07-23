# Maven Public Repository

Our Github Maven Repository Entry

## Usage

### Maven

```xml
<repository>
    <id>github</id>
    <url>https://maven.pkg.github.com/shinonometn/maven-public</url>
    <!-- Optional, force enable snapshot version -->
    <snapshots>
        <enabled>true</enabled>
    </snapshots>
</repository>
```

### Gradle 

```groovy
repositories {
    maven { url = "https://maven.pkg.github.com/shinonometn/maven-public" }
}
```

For all out library please also check this out:

```
https://nexus.shinonometn.com/repository/maven-public/
```
