# "Batteries included" prototool pre-commit hook

Example `.pre-commit-config.yaml`:

```yaml
# See https://pre-commit.com.
repos:
  - repo: https://github.com/marvin-the-mathematician/pre-commit-prototool
    rev: v1.9.0
    hooks:
      - id: "prototool:1.9.0"
        name: prototool lint
        args: ["lint"]
```

Links:

- https://github.com/uber/prototool
- https://pre-commit.com
