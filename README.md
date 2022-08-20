Go to src/main/resources/docker/ and run

```
docker compose up db
```

After in the base directory run the following maven command. It will show some information was stored in MongoDB


```
mvn spring-boot:run
```

The liqubase configuration has some problems:
```
mvn liquibase:status
```


