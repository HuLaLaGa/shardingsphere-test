# ShardingSphere-Test

> This project reproduce 'connection disabled' Exception when use both ShardingSphere and Druid
> 
> src/test/java/com/hulalaga/ShardingSphereTest.java
> 

```shell
mvn -T 1C clean test 
```

```text
[INFO]
[INFO] Results:
[INFO]
[ERROR] Failures:
[ERROR]   ShardingSphereTest.testDruidConnectionDisabled:97 Unexpected exception thrown: org.springframework.jdbc.UncategorizedSQLException: StatementCallback; uncategorized SQLException for SQL [select '']; SQL state [null]; error code [0]; connection disabled; nested exception is java.sql.SQLException: connection disabled
[INFO]
[ERROR] Tests run: 1, Failures: 1, Errors: 0, Skipped: 0
```