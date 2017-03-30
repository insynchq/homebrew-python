# Insync Homebrew Taps

These are [Homebrew](http://brew.sh/) taps for installing specific versions of dependencies required for Drivebox development.

## Usage

If you previously installed these using the default formulae:

```
brew uninstall python
brew uninstall libevent
```

Then:

```
brew tap insynchq/taps
brew install python2-universal
brew install libevent-2.0.22
```

## Python

Homebrew has decided to [drop support for universal builds](https://github.com/Homebrew/homebrew-core/pull/9641#issuecomment-280746019).

This tap just adds that support back, i.e., reverts the change in [this commit](https://github.com/Homebrew/homebrew-core/commit/3538e06db9b1e4e4eef3fbc4ba84acadd66a4362).

## `libevent`

This is a formula for installing `libevent` version 2.0.22.
