# Homebrew Composer

This repository contains a Homebrew formula for installing
[Composer](https://getcomposer.org) that depends on [shivammathur/php](https://github.com/shivammathur/homebrew-php) instead of php
from homebrew/core.

```shell
# Add tap
brew tap nhedger/composer

# Update homebrew
brew update

# Install composer
brew install nhedger/composer/composer
```

## Sync

This formula is kept in sync with the [composer formula in homebrew/core](https://formulae.brew.sh/formula/composer)
using a GitHub Actions workflow triggered every 12 hours.