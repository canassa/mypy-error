# mypy-error

A project that crashes mypy

## Usage


```
mypy src
```

Expected output

```
src/file_a.py:4: error: Function is missing a return type annotation
src/file_a.py:4: note: Use "-> None" if function does not return a value
src/file_a.py:4: error: INTERNAL ERROR -- Please try using mypy master on Github:
https://mypy.rtfd.io/en/latest/common_issues.html#using-a-development-mypy-build
If this issue continues with mypy master, please report a bug at https://github.com/python/mypy/issues
version: 0.720
src/file_a.py:4: : note: please use --show-traceback to print a traceback when reporting a bug
```