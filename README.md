# Pytree 
This is a simple project for create command line tool like `tree` in linux.

# Entry virtual environment
```
cd pytree
. venv/bin/activate
python setup.py develop
```

# Run test
```
pytest
```

# Build excuteable file
```
pyinstaller -F pytree/pytree.py --clean
```
