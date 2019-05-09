#### "Hello World" java program

Source:
```java
// File name: HelloWorld.java
public class HelloWorld {

    // program execution starts from here
    public static void main(String[] args) {
        System.out.println("Hello, World !");
    }

}
```

Output:
```plain
Hello, World !
```

### Running a java program
Running java program includes two steps
#### 1. Compilation
In this stage java code (.java) compiled into [JVM](https://en.wikipedia.org/wiki/Java_virtual_machine) understandable code (.class).
```sh
javac HelloWorld.java
```
> The `javac HelloWorld.java` command\
> Reads the **HelloWorld.java** file\
> Check syntax errors in the code, and prints the errors\
> If no syntax errors were found, then generates the **HelloWorld.class** file


#### 2. Execution
In this stage compiled code (.class) file executed by [JVM](https://en.wikipedia.org/wiki/Java_virtual_machine)
```sh
java HelloWorld
```
> The `java HelloWorld` command\
> Start the [JVM](https://en.wikipedia.org/wiki/Java_virtual_machine)\
> Feed the **HelloWorld.class** file to [JVM](https://en.wikipedia.org/wiki/Java_virtual_machine) for executing