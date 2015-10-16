# homebrew-snakefarm

Homebrew formulas for Python versions older than most recent minor version in Homebrew itself.

These versions are installed using the `altinstall` scheme, which makes their executables available only as `pythonX.Y`, in order to not interfere with the standard `python` and `python3` executables. Each minor version has its own `site-packages`, and a corresponding `pipX.Y` executable.

Available versions:

- Python 3.4
- Python 3.3

## Usage

```bash
brew tap byfilip/snakefarm
brew install python34
brew install python33
```

## Bugs

`readline` support in Python 3.3 isn't working. Try `pip3.3 install gnureadline` after install.
