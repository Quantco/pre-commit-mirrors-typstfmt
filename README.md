# typstfmt pre-commit hook

pre-commit hook of typstfmt with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For typstfmt: see [here](https://github.com/astrale-sharp/typstfmt)

## Using typstfmt with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-typstfmt
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: typstfmt-conda
```
