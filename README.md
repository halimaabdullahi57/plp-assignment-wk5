# PLP Python Week 5 - Password Generator & Your Own Module

## Files
- `password_generator.py` - Uses Python's built-in `random` and `string` modules to generate passwords.
- `helpers.py` - A custom module containing `tables_needed()` and `welcome()`.
- `main.py` - Imports the custom `helpers` module and uses its functions.

## How to run

### Password Generator
```bash
python password_generator.py
```

It generates one 8-character password and one 12-character password. Run it twice to show that the passwords are different.

### Custom Module
Run:
```bash
python main.py
```

Expected output:
```text
Welcome to PLP, Amina!
8
4
```

Then run:
```bash
python helpers.py
```

Expected output:
```text
3
```

The `if __name__ == "__main__":` condition makes the final `3` print only when `helpers.py` is run directly.
