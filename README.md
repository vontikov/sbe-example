# Project layout

| Folder                 | Description  |
| ---------------------- | -------------|
| src/main/java          | Java sources |
| src/main/resources/sbe | SBE schemas  |
| src/generated/java     | Java codecs  |

# Generate codecs 

Java codecs should be generated time the SBE schema has changed

```
gradle sbeGenerateJavaCodecs
```

# Build

```
gradle fatJar
```

# Run

```
java -jar build/libs/sbe-example-all.jar
```