# ShinonomeTN Maven Public Repository

## Usage

### Maven

```xml
<repository>
    <id>github</id>
    <url>https://nexus.shinonometn.com/repository/maven-public/</url>
    <!-- Optional, force enable snapshot version -->
    <snapshots>
        <enabled>true</enabled>
    </snapshots>
</repository>
```

### Gradle 

```groovy
repositories {
    maven { url = "https://nexus.shinonometn.com/repository/maven-public/" }
}
```

Organization members can check this out:

```
https://maven.pkg.github.com/shinonometn/maven-public
```

## Attentions

⚠️ For saving disk usage, we will clear snapshot versions in maven-public after every month.
