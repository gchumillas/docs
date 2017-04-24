# General docs
General docs about Python environment.

## Create a bash script

Create a `script.py` file:
```python
#!/usr/bin/env python

""" This script does something... """

print 'Something!'
```

and then make it executable:
```bash
chmod +x script.py
```

## Use `pylint` to find coding standards issues

Generate the pylint config file
```bash
pylint --generate-rcfile > .pylintrc
```
And edit this line to disable full report messages
```text
reports=no
```
Now you can find coding standards leaks:
```bash
pylint my-script.py
```
