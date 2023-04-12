# ShinonomeTN Maven Public Repository

Our dependency repository is primarily used to meet our daily development and sharing needs.

The repository is non-profit and is selflessly funded by some of our members.
We do not guarantee its 100% availability and distribution timeliness, but we do our best to keep it up and running.

## Usage

### Maven

```xml
<repository>
    <id>shinonometn-maven-public</id>
    <url>https://nexus.shinonometn.com/repository/maven-public/</url>
    <!-- Optional force enabling snapshot version -->
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

For how to use, please check Github's repo instructions.

## Attentions

⚠️ For disk usage saving, snapshot versions in `maven-public` will be cleared monthly.
