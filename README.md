### jnr-ffi
---
https://github.com/jnr/jnr-ffi

```java
package helloworld;

impor jnr.ffi.LibraryLoader;

public class HelloWorld {
  public static interface LibC {
    int puts(String s);
  }
   
  public static void main(String[] args) {
    LibC libc = LibraryLoader.create(LibC.class).load("c");
    
    libc.puts("Hello, World!");
  }
}

@pit_t long getpid();
@ssize_t long read(int fd, Pointer data, @size_t long len);
```

```
```

```
```


