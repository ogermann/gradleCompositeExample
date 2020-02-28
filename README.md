# gradleCompositeExample
Example project to showcase an issue in gradle 6.2

# How to reproduce the issue
First we run a project on gradle 6.2, which should fail with an assertion error.
```
cd ./projectA && ./gradlew tasks
```

Second we run a project on gradle 6.1.1 which should work.
```
cd ../projectC && ./gradlew tasks
```
