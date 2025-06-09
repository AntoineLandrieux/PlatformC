
# Platform C

Platform C is used in [SOARE](https://github.com/AntoineLandrieux/SOARE/).

---

## Why a repository for that?

Header files are essential components that contain definitions of functions, macros, constants, and data types...

Here this header defines a preprocessor (`__PLATFORM__`) constant that contains the name of the operating system where the program was compiled.

By contributing, we can add more cases for different operating systems by using only preprocessor directives. (using `gcc` [[GNU C Compiler](https://gcc.gnu.org/)] compiler)

## Documentation

```c

#include <stdio.h>
#include <stdlib.h>

#include "platform.h"

int main(int argc, char *argv[])
{
    printf("Hello !\nCurrent OS: %s\n", __PLATFORM__);
    return EXIT_SUCCESS;
}
```

## Contributing

The Platform C source code is located in the Git repository at [github.com/AntoineLandrieux/PlatformC](https://github.com/AntoineLandrieux/PlatformC/).
Contributions are most welcome by forking the repository and sending a pull request.

## Credit

See **[SOARE REPO](https://github.com/AntoineLandrieux/SOARE/)**

**Contributors :**

![contributors](https://contrib.rocks/image?repo=AntoineLandrieux/PlatformC)
