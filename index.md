# H1 header
That is my first
# h1 header v2
![Image to Yaktocat](https://octodex.github.com/images/yaktocat.png)
```Java
package com.vorobey.lesson20.exception;

import java.io.FileNotFoundException;

public class ExceptionExample {
    public static void main(String[] args) {
        System.out.println("Main start");
        try {
            unsafe(-10);
        } catch (FileNotFoundException e) {
            e.printStackTrace();
            System.out.println("catched bitch()");
        } finally {
            System.out.println("finally ends");
        }
        System.out.println("main end");
    }

    public static void unsafe(int value) throws FileNotFoundException {
        System.out.println("unsafe start");
        if (value > 0) {
            throw new FileNotFoundException();
        }
        System.out.println("unsafe end");
    }
}
```

- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world 
