# mac-setup-tutorial


Install brew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Add brew into path
```
vim ~/.zshrc
```

Add brew's $PATH into .zshrc then restart terminal
```
export PATH="/opt/homebrew/bin:$PATH"
```

Install git
```
brew install git
```

Config git
```
git config --global user.email "email@example.com"
```

Install python
