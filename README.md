# Header 1

## Header 2

### Header 3

#### Header 4

Some text

And some code example

```java
return fileLines.flatMap(s -> Stream.of(s.split("[\\s.,;:?!\\n\\r\\]\\[]+")))
        .map(String::toLowerCase)
        .filter(s -> !s.isEmpty())
        .collect(Collectors.groupingBy(Function.identity(), Collectors.counting()));
```
