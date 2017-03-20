namesgenerator
==============

Docker names generator, ported to Python.

### Installation for standalone use

Just clone the run `python namesgenerator.py` in a terminal.

```
$ python namesgenerator.py
jolly_wozniak
```

### Installation into your project

Just copy `namesgenerator.py` to your project: 

```curl -O https://raw.githubusercontent.com/shamrin/namesgenerator/master/namesgenerator.py```

### Usage

```python
>>> import namesgenerator
>>> print namesgenerator.get_random_name()
hopeful_morse
>>> for i in range(5):
...   print namesgenerator.get_random_name()
...
angry_torvalds
jolly_nobel
happy_almeida
sleepy_kowalevski
happy_almeida
```

### Other implementations

* [Go][2] (original)
* [JavaScript][1]

[1]: https://github.com/tonypujals/docker-namesgenerator
[2]: https://github.com/docker/docker/blob/master/pkg/namesgenerator/names-generator.go
