puppet-stumpwm
==============

A simple puppet module to ease the install of stumpwm.

# use

## install via git

This is designed at the moment to be built up with git.

Add this project as a submodule

``` git
git submodule add git@github.com:ardumont/puppet-stumpwm.git /path/to/puppet/modules/folder/stumpwm
```

## Use

### static config

init.pp:

``` puppet
include stumpwm
```

### ENC

`your-node.yaml`:

``` yaml
  stumpwm:
```
