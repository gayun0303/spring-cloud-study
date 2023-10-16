# spring-cloud-study

Spring Cloud로 개발하는 마이크로서비스 애플리케이션(MSA)

## Service Discovery

### maven 대신 gradle로 프로젝트 실행 방법

- gradle (4.9 이상)

```shell
$./gradlew bootRun --args='--server.port=9003'
```

- gradle로 jar build

```shell
$./gradlew build
```

- java jar

```shell
$java -jar "-Dserver.port=9004" /buld/libs/user-service-0.0.1-SNAPSHOT.jar
```

- cmd 창에서 실행 시 `./gradlew` 대신 `gradlew` 사용
