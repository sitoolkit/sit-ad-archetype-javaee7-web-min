## Usage (Windows)
```bat
set JAVA_HOME=<jdk installed directory>

cd <projct base directory>
start mvn -P derby
mvn -P flyway
mvn -P hibernate-tools

set MAVEN_REPO=<maven local repository directory>
mvn install
start mvn -P was-liberty
```

## Open URL
<http://localhost:8080/>

