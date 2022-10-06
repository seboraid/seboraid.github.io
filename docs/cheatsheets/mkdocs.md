# Snippets para crear la doc del sitio

[Referencias](https://squidfunk.github.io/mkdocs-material/reference/)

!!! note "Recuadro"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

??? note "Recuadro Desplegable"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

???+ note "Recuadro Desplegable Expandido"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

:fontawesome-brands-js:{ .jscolor } Javascript
:octicons-heart-fill-24:{ .sbd-heart } corazón
:fontawesome-brands-twitter:{ .twitter } pajarón
:fontawesome-brands-aws:{ .sbd-aws } aws


## Bloques de código

YAML:

``` yaml
theme:
  features:
    - content.code.annotate # (1)!
```

PYTHON:

- sin título

``` py
import tensorflow as tf
```

- con título

``` py title="file.py"
import tensorflow as tf
```

- con número de línea

``` py title="file.py" linenums="1"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

- con número de línea y resaltado 

``` py title="file.py" hl_lines="2 4" linenums="1"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

- Bloques de código agrupados

=== "C"

    ``` c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "C++"

    ``` c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```

- Bloques de código agrupados y dentro de una anotación

???+ note "Código Hello World"

    === "C"

        ``` c title="hello.c"
        #include <stdio.h>

        int main(void) {
        printf("Hello world!\n");
        return 0;
        }
        ```

    === "C++"

        ``` c++ title="hello.cc"
        #include <iostream>

        int main(void) {
        std::cout << "Hello world!" << std::endl;
        return 0;
        }
        ```


!!! example

    === "Unordered List"

        ``` markdown
        * Sed sagittis eleifend rutrum
        * Donec vitae suscipit est
        * Nulla tempor lobortis orci
        ```

    === "Ordered List"

        ``` markdown
        1. Sed sagittis eleifend rutrum
        2. Donec vitae suscipit est
        3. Nulla tempor lobortis orci
        ```
