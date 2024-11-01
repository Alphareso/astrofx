# astrofx
Re-create non-modular project to run with Maven.

[![Maven Central](https://img.shields.io/maven-central/v/org.openjfx/javafx-maven-archetypes.svg?color=%234DC71F)](https://search.maven.org/#search|ga|1|org.openjfx.javafx-maven-archetypes)
[![BSD-3 license](https://img.shields.io/badge/license-BSD--3-%230778B9.svg)](https://opensource.org/licenses/BSD-3-Clause)

### Prerequisite

* JDK 17.0.12
* JavaFX 17.0.13
* Maven 3

### Commandline
```
mvn archetype:generate -DgroupId=com.astrofx -DartifactId=my-javafx-app -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
```
### Compile
```
mvn package
```
### Run
```
java --module-path /path/to/javafx-sdk-17/lib --add-modules javafx.controls,javafx.fxml -jar target/astrofx-1.0-SNAPSHOT.jar
```

Hope your project goes smoothly! 🚀✨
