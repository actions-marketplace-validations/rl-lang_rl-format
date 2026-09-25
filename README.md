# rl-format

Fails on badly formatted `.rl` files. Never modifies your tree (checks against a copy).

```yaml
- uses: rl-lang/rl-format@main
  with:
    folder: src/
```

| Input | Default |
|---|---|
| `version` | `latest` |
| `file` | `''` |
| `folder` | `''` |
| `working-directory` | `.` |

One of `file` or `folder` is required.
