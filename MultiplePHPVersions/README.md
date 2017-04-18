# Purpose

The purpose of these files is to handle running multiple versions of PHP in your local MacOS environment.

# Getting started

- Install [Laravel Valet](https://github.com/laravel/valet)
- `brew install php56`

# Adding the command

Copy the contents of `toggle_php_versions` and place it in a file in your user's bin directory.

```bash
vim ~/bin/toggle_php_versions
# Paste the contents into the file
chmod 755 ~/bin/toggle_php_versions
```

# Switching versions

To switch versions, all you should need to do is run `toggle_php_versions`.
