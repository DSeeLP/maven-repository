# Maven Repository
## How to use
### Gradle
Put this into your repositories block if you are using the kotlin dsl:
```
maven(url = "https://raw.github.com/DSeeLP/maven-repository/main/")
```
Use this when you are using the groovy dsl:
```
  maven {
    url 'https://raw.github.com/DSeeLP/maven-repository/main/'
  }
```

### Maven
Put this in your repositories block:
```xml
    <repository>
      <id>dseelp</id>
      <name>your custom repo</name>
      <url>https://raw.github.com/DSeeLP/maven-repository/main/</url>
    </repository>
```
