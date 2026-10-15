# Steps
## Package
```
rm -rf dist/
pip wheel . -w dist/ --no-deps
```

## Publish
```
twine upload dist/*
```