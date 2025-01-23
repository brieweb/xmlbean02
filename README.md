# xmlbean02
Practice XMLBean code

This is a Maven adapted example from the XMLBeans project. [Date Example](https://xmlbeans.apache.org/samples/DateTime.html)

Set your Java Home. This assumes you are using Java 21. Adapt accordingly.

```
export JAVA_HOME=/usr/lib/jvm/java-21-openjdk
```

Compile. This will generate the sources from the schema and compile all java sources. 

```
$ mvn clean generate-sources compile
```

Run 

```
$ mvn exec:java
```
