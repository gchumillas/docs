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

```bash
# generate an pylint config file
pylint --generate-rcfile > .pylintrc

# find coding standards issues
pylint my-script.py
```
