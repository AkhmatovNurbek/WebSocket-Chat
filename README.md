# WebSocket-Chat
 <img align="left" src="https://github.com/AkhmatovNurbek/WebSocket-Chat/blob/master/src/main/resources/img.png" alt="java" height="80px"/> 
 
 

## Getting Started

### Dependency management tools

Below is a brief guide to using dependency management tools like maven or gradle.

#### Maven
To use maven add this dependency to your pom.xml:
```xml
<dependency>
  <groupId>org.java-websocket</groupId>
  <artifactId>Java-WebSocket</artifactId>
  <version>1.5.3</version>
</dependency>
```

#### Gradle
To use Gradle add the maven central repository to your repositories list:
```xml
mavenCentral()
```
Then you can just add the latest version to your build.
```xml
compile "org.java-websocket:Java-WebSocket:1.5.3"
```
Or this option if you use gradle 7.0 and above.
```xml
implementation 'org.java-websocket:Java-WebSocket:1.5.3'
```

#### Logging

This library uses [SLF4J](https://www.slf4j.org/) for logging and does not ship with any default logging implementation.

Exceptions are using the log level `ERROR` and debug logging will be done with log level `TRACE`.

Feel free to use whichever logging framework you desire and use the corresponding [binding](https://mvnrepository.com/artifact/org.slf4j) in your dependency management.

If you want to get started, take a look at the SimpleLogger [example](https://github.com/TooTallNate/Java-WebSocket/wiki/SimpleLogger-example).

### Standalone jar

If you do not use any dependency management tool, you can find the latest standalone jar [here](https://github.com/TooTallNate/Java-WebSocket/releases/latest).
