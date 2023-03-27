cython-lint(-conda) mirror
====================

Mirror of cython-lint for pre-commit with conda as a language.

For pre-commit: see https://github.com/pre-commit/pre-commit
For cython-lint: see https://github.com/MarcoGorelli/cython-lint

### Using cython-lint with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/Quantco/pre-commit-mirrors-cython-lint
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: cython-lint-conda
```

