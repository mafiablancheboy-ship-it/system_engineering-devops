# 0x03. Shell, init files, variables and expansions

This project introduces:
- Shell initialization files (`/etc/profile`, `~/.bashrc`)
- Local vs. global variables
- Reserved variables
- Creating and exporting variables
- Expansions:
  - Command substitution
  - Arithmetic expansion
  - Brace expansion
  - Parameter expansion
- Aliases

## Scripts Description

| Script | Description |
|--------|-------------|
| `0-alias` | Creates an alias `ls` → `rm *` |
| `1-hello_you` | Prints `hello <user>` where `<user>` is the current Linux user |
| `2-path` | Adds `/action` to the `PATH` environment variable |
| `3-paths` | Counts the number of directories in `$PATH` |
| `4-global_variables` | Prints all global environment variables |
| `5-local_variables` | Prints local, environment, and functions |
| `6-create_local_variable` | Creates a local variable `BEST="School"` |
| `7-create_global_variable` | Creates a global variable `BEST="School"` |
| `8-true_knowledge` | Prints the result of `$TRUEKNOWLEDGE + 128` |
| `9-divide_and_rule` | Prints the result of `$POWER / $DIVIDE` |
| `10-love_exponent_breath` | Prints `$BREATH` to the power of `$LOVE` |

All scripts follow ALX checker formatting requirements.

---

## How to Use
Make each script executable:
```bash
chmod +x <scriptname>
