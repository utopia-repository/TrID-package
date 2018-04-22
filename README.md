# TrID-package

The `trid-package` utility automatically downloads and builds a Debian/Ubuntu (.deb) package for the latest upstream version of [TrID](http://mark0.net/soft-trid-e.html).

## License

This downloader utility is licensed under MIT/Expat (see [LICENSE](LICENSE)).

However, TrID itself (and thus the generated .deb's) are *not* DFSG-free. The license of TrID is as follows:

```
License:
The program can be freely distributed and is freeware for non commercial,
personal, research and educational use.
Contact the author for commercial use or commercialization of TrID or
TrID's definitions and contained informations.
```

## Requirements

- unzip
- wget
- gpg (for signature verification)
- The Debian packaging toolchain (devscript, dpkg-deb)
