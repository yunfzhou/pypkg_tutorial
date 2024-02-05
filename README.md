## pypkg_tutorial

- This is a simple package tutorial.
- The full tutorial can be found at https://makeoptim.com/python/pypi-pkg

### How to install

```
python -m pip install --index-url https://test.pypi.org/simple/ --no-deps pypkg_tutorial
```

### How to use

```python
from pypkg_tutorial import hello

hello.hello_world()
```

Output:

```
Hello, world!
```