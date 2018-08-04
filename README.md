# Design Patterns

# Most of this repo python_implementation come from [python-patterns](https://github.com/faif/python-patterns).

    difference: Change from py2 -> py3 or add some flavor(doctest etc.) :)

A collection of design patterns and idioms in Python/Go.

- Python

    |pattern keyword|description|Note|
    |:-------------:|:----------|:---|
    |singleton|a singleton with shared-state among instances|多实例共享状态, 仅就共享状态而言可以有N种方法达到|
    |registory|keep track of all subclasses of given class|利用元类或之类的手段, 在实例化时在某处(元类空间)中注册信息|
    |strategy|selectable operations over the same data|本质还是方法复写|
----------

- Go

    |pattern keyword|description|Note|
    |:-------------:|:----------|:---|