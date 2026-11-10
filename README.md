# homebrew-sidle

Homebrew tap for [Sidle](https://github.com/rp6186030/sidle), trackpad edge gestures for macOS.

```bash
brew install --cask rp6186030/sidle/sidle
```

If Homebrew says the tap is untrusted, run `brew trust rp6186030/sidle` and install again.

Sidle is not notarized. If macOS refuses to open it, run once:

```bash
xattr -dr com.apple.quarantine /Applications/Sidle.app
```
