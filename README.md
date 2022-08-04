# mac-python-setup-tutorial


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
ESC
:wq
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
```
arch -x86_64 /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
alias ibrew="arch -x86_64 /usr/local/bin/brew"
ibrew install python@3.7
```

Add python to path
```
echo "export PATH="/usr/local/opt/python@3.7/bin:$PATH"" >> ~/.zshrc
```
