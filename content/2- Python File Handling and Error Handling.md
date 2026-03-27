## Phase 7: File Handling

### 7.1 Reading and Writing Files

- Opening files: `open()` with modes (`r`, `w`, `a`, `rb`)
- Using `with` statement (context manager)
- Reading: `.read()`, `.readline()`, `.readlines()`
- Writing: `.write()`, `.writelines()`
- Closing files properly

### 7.2 Working with File Paths

- Absolute vs relative paths
- Using `os.path` for path manipulation
- `pathlib.Path` (modern approach)

### 7.3 Working with CSV and JSON

- Reading/writing CSV with the `csv` module
- Reading/writing JSON with the `json` module
- `json.loads()` vs `json.load()`
- `json.dumps()` vs `json.dump()`

---

## Phase 8: Error Handling

### 8.1 Understanding Errors

- Syntax errors vs runtime errors vs logical errors
- Common built-in exceptions:
  - `TypeError`, `ValueError`, `IndexError`
  - `KeyError`, `FileNotFoundError`, `ZeroDivisionError`

### 8.2 Try / Except Blocks

- Basic `try` / `except`
- Catching specific exceptions
- `else` block — runs if no exception
- `finally` block — always runs
- Raising exceptions with `raise`

---
