# Python Extended (PyE)

PyE is an extension to the Python programming language (kinda like C++ is to C) and the first of it's kind, the first **Dynamic** language. Many dynamically typed languages have been developed ever since the first language was created but no one thought of creating a dynamic language so here it is.

## What extension to Python

- Python is very popular for it's ease of use and simple syntax including it's dunder methods.
- PyE adds just one simple magic method and a attribute which will instead keep nothing simple.
- You must have all seen the special syntaxes in Python for e.g. [] (list), {} (dict), "" (string), 123 (int) etc. which extend up it's simple syntax but the question is `Why only these types have special syntaxes? Why can't others have it?` The solution is simple, Python Extended (PyE).
- The new dunder method is `__parse__(self)` this method will take only one argument, `self`. Interesting thing is that it will be instanciated with the `Interpreter` object itself.
- This method will be called when
