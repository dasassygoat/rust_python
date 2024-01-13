# To use Maturin the following steps are required:

1. `python3 -m venv .env`
2. `source .env/bin/activate`
3. `pip install maturin`
4. `maturin init`
5. Create necessary python file : `touch examples/example.py`

```
    import name_of_project

    result = name_of_project.sum(1, 2)
    return(result)
```

6. `maturin develop` and select **pyo3**
7. `python3 examples/example.py `
