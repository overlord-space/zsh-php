# zsh-php
Work easily with multiple PHP versions installed via [Homebrew](https://brew.sh)

# Installation
`git clone https://github.com/KobaltMR/zsh-php.git ~/.zsh-php && echo "\nsource ~/.zsh-php/zsh_php\n" >> ~/.zshrc`

# Usage examples
```
php74 -v
php8  -v
php80 -v
php81 -v
```

Universal command:
```
_php <version> <arguments>
```

You can also work with composer in the following way:
```
php81 composer <args>
_php 8.1 composer <args>
```
