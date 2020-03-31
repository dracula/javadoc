### [Javadoc](https://docs.oracle.com/javase/8/docs/api/)

#### Install

Download the [stylesheet](https://raw.githubusercontent.com/dracula/javadoc/master/styles/dracula-javadoc8.css)

If you are using gradle, add below to javadoc options:
```groovy
    javadoc {
        options.stylesheetFile = new File(projectDir, "path/to/your/resource/dracula-javadoc8.css")
        // And some options...
    }
```

If you are using maven, add below to plugin option:
```xml
    <plugin>
      <groupId>org.apache.maven.plugins</groupId>
      <artifactId>maven-javadoc-plugin</artifactId>
      <configuration>
        <stylesheetfile>path/to/your/resource/dracula-javadoc8.css</stylesheetfile>
        ...
      </configuration>
    </plugin>
```
