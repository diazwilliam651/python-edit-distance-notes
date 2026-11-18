# Measure Levenshtein distance: implementation

## What the example does

Dynamic programming counts insertions, deletions and substitutions with unit cost. This implementation uses one previous row but still takes quadratic time.

The public function is `solve(value)`. The JSON input contract can be seen in this concrete example:

```json
[
  "kitten",
  "sitting"
]
```

Expected result:

```json
3
```

Run `python3 example.py` for the Python representation of the result. `solution.py` contains the full implementation and can also be imported by another script.

## Scope

The function implements exactly the behavior described above. It does not perform network or filesystem access. Python exceptions indicate unsupported input; the next lesson turns them into a command-line error response. Review the limitations before reusing it in an application.
