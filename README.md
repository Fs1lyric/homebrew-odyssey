# homebrew-odyssey

A [Homebrew](https://brew.sh) tap for [Odyssey Design](https://github.com/Fs1lyric/odyssey-design).

```bash
brew install --cask fs1lyric/odyssey/odyssey-design
```

Universal by way of two disk images: Apple silicon and Intel each get their
own, with their own checksum.

The application is **not notarized**. macOS will refuse the first launch until
you allow it in System Settings, under Privacy and Security. The cask says so
in its caveats rather than hiding it.

The cask is generated from the release by `packaging/sync-release.sh` in the
main repository. Edit it there, not here.
