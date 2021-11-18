Maven Specify Java Version Demo
================================

如何设置jdk版本

注意：当前使用的jdk版本要大于等于指定的，才能正确运行。

```
mvn clean compile exec:java -Dexec.mainClass="demo.Hello"
```

