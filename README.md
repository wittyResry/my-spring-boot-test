# 1. Ref:
* https://docs.spring.io/spring-boot/docs/current/reference/html/getting-started-first-application.html

# 2. run by mvn

```bash
$ mvn spring-boot:run
```

# 3. run by jar

```bash
$ mvn package
$ cd  target
$ java -Xdebug -Xrunjdwp:transport=dt_socket,address=8000,server=y,suspend=n -jar  my-spring-boot-test-0.0.1-SNAPSHOT.jar 
```
