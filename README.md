# Python Extended (PyE)

PyE is an extension to the Python programming language, much like C++ is to C. It's the first of its kind: the first **dynamic** language. Many dynamically-typed languages have been developed over the years, but no one has thought of creating a truly dynamic language until now.

## What is Python Extended (PyE)?

- Python is popular for its ease of use and simple syntax, including its dunder methods.
- PyE introduces a single magic method and attribute that revolutionize simplicity.
- You've seen Python's special syntaxes like `[]` for lists, `{}` for dictionaries, `""` for strings, `123` for integers, etc. But why do only these types have special syntaxes? Why can't others?
- Enter Python Extended (PyE). The solution to this question is simple.

## New Dunder Method

- The new dunder method `__parse__(self)` only takes one argument: `self`. Interestingly, it is instantiated with the `Interpreter` object itself.
- This method is invoked when the `__schar__` attribute, which must always be a string or a list of strings, appears during code execution.
- One can also use labels, for eg. ```dict:{"A": "B"}```, to tell the `Interpreter` to parse the specific type.
- This new method will change everything, this means that in PyE everthing can be an object even statements. For eg. ```type(type(dict)):class A: pass```
- This way new language features can be added even as a modules making PyE truely dynamic.
