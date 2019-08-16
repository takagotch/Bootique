### bootique
---
https://github.com/bootique/bootique

https://bootique.io/

```java
package com.foo;

import io.bootique.Bootique;

public class Application {
  public static void main(String[] args) {
    Bootique
      .app(args)
      .autoLoadModules()
      .exec()
      .exit();
  }
}
```

```
```

```
```
