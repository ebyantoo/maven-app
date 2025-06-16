# Maven APP

```
mvn archetype:generate \
  -DgroupId=com.marak.app \
  -DartifactId=maven-app \
  -DarchetypeArtifactId=maven-archetype-quickstart \
  -DinteractiveMode=false


<properties>
  <maven.compiler.source>21</maven.compiler.source>
  <maven.compiler.target>21</maven.compiler.target>
</properties>


```


```
package com.marak.app;

public class App {
    public static void main(String[] args) {
        System.out.println("Halo dari Java 21 + Maven!");
    }
}


mvn clean package
java -jar target/maven-app-1.0-SNAPSHOT.jar


```