# delegate-demo-request - A simple demo request :rocket:

<br /><br />
![Java](https://img.shields.io/badge/Java-17-green?style=plastic&logo=java)
![Spring Boot](https://img.shields.io/badge/SpringBoot-2.7.4-green?style=plastic&logo=spring)
![Maven](https://img.shields.io/badge/Maven-green?style=plastic)

That project is a sample that can be used for any kind of requests
<br />

### Requirements ###

* Java 17
* Maven 3.3.x

### Building the artifact ###

```
mvn clean package
```

### Running the application from command line ###

```
mvn spring-boot:run -Dserver.port=8800
```

### Available URLs

```
http://localhost:8800/demo
```

should result in successful responses.