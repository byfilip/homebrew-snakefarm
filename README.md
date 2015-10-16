# homebrew-snakefarm

`altinstall` formulas for Python versions older than most recent minor version in Homebrew.

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
