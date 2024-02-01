# cython-lint pre-commit hook

pre-commit hook of cython-lint with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For cython-lint: see [here](https://github.com/MarcoGorelli/cython-lint)

## Using cython-lint with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-cython-lint
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: cython-lint-conda
```
