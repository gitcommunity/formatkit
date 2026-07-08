
```python
pip install formatkit
```

### How to use it?
```python
from formatkit import text, background, formats, default
print(text.red+"Red text"+default)
print(background.red+"Red background"+default)
print(format.italic+"Italic text"+default)
print(format.spoiler+"Spolier text"+default)
```

### Code Table

| TYPE | DESC | ANSI |
|-------|---------|----------|
| text | black | `\x1b[30m` |
| text | red | `\x1b[31m` |
| text | green | `\x1b[32m` |
| text | yellow | `\x1b[33m` |
| text | blue | `\x1b[34m` |
| text | magenta | `\x1b[35m` |
| text | cyan | `\x1b[36m` |
| text | white | `\x1b[37m` |
| text | default | `\x1b[39m` |
| background | black | `\x1b[39m` |
| background | red | `\x1b[41m` |
| background | green | `\x1b[42m` |
| background | yellow | `\x1b[43m` |
| background | blue | `\x1b[44m` |
| background | magenta | `\x1b[45m` |
| background | cyan | `\x1b[46m` |
| background | white | `\x1b[47m` |
| background | default | `\x1b[49m` |
| formats | default | `\x1b[22m` |
| formats | bold | `\x1b[1m` |
| formats | dim | `\x1b[2m` |
| formats | italic | `\x1b[3m` |
| formats | underline | `\x1b[4m` |
| formats | spoiler | `\x1b[7m\x1b[8m` |
| (module) | default | `\x1b[0m` |
