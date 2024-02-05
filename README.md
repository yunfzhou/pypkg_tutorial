## pypkg_tutorial

- This is a simple package tutorial.
- The full tutorial can be found at https://makeoptim.com/python/pypi-pkg
- The project information can be found at https://test.pypi.org/manage/project/pypkg-tutorial/releases/

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