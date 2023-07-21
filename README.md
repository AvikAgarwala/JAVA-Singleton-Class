# Singleton Class Implementation in JAVA

## Introduction

This repository contains a Java implementation of the Singleton design pattern. The Singleton pattern ensures that a class has only one instance. This can be useful in scenarios where you want to restrict the instantiation of a class to a single object.

`Type-1` implementation: This implementation restricts the user to create more than one object of the singleton class.

`Type-2` implementation: In this implementation every object of the singleton class points to the same memeory location.

### How to compile

1. Go inside `Type-1` or `Type-2` directory.
```bash
cd Type-1
```
or,
```bash
cd Type-2
```

2. Compile using java compiler.
```java
javac singleton.java
```
🗃️ Note: This will create two .class files inside current directory: `Singleton.class` & `Main.class`
### How to run

- Run using java interpreter.
```java
java Main
```
### Output
- for `Type-1` implementation
```
Object has been created!
This is a singleton class! Cannot create more objects!
This is a singleton class! Cannot create more objects!
1
Exception in thread "main" java.lang.NullPointerException: Cannot read field "id" because "<local2>" is null
        at Main.main(singleton.java:30)
```

- for `Type-2` implementation
```
1
1
1
```
