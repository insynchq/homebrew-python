# Insync Homebrew Taps

These are [Homebrew][brew] taps for installing specific versions of dependencies required for Drivebox development.

## Usage

```
brew tap insynchq/taps
brew install insynchq/taps/python2-universal
brew install insynchq/taps/libevent-2.0.22
```

## Python

Homebrew has decided to [drop support for universal builds][drop-universal-support].

This tap just adds that support back, i.e., reverts the change in [this commit][commit].

## `libevent`

This is a formula for installing `libevent` version 2.0.22.

[brew]: http://brew.sh/
[drop-universal-support] https://github.com/Homebrew/homebrew-core/pull/9641#issuecomment-280746019
[commit]: https://github.com/Homebrew/homebrew-core/commit/3538e06db9b1e4e4eef3fbc4ba84acadd66a4362
