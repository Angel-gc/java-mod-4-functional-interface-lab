# Functional Interface Lab

## Instruction

Create a functional interface called `ConcatStringFunction` that has a method
called `apply` that takes in a variable amount of `String` arguments and returns
a `String` values.

Here’s an example of how your method would be called:

```java
public class Main {
    public static void main(String[] args) {
        ConcatStringFunction func = str -> String.join("", str).toUpperCase();
        String res = func.apply("banana", "grape", "smoothie");
        System.out.println(res); // BANANAGRAPESMOOTHIE

				String res2 = func.apply("apple", "orange", "pineapple", "smoothie");
				System.out.println(res); // APPLEORANGEPINEAPPLESMOOTHIE
    }
}

@FunctionalInterface
// your code here
```
