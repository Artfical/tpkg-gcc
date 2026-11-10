# gcc

GCC 15.3.0: gcc, g++, cpp (C and C++ compilers; 64-bit tOS)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install gcc
```

| | |
|---|---|
| Version | 15.3.0-2 |
| Licence | GPL-3.0+ with GCC Runtime Library Exception |
| Upstream | https://gcc.gnu.org |
| Needs | [`binutils`](https://github.com/Artfical/tpkg-binutils), [`glibc-dev`](https://github.com/Artfical/tpkg-glibc-dev), [`make`](https://github.com/Artfical/tpkg-make) |
| Needs tOS build | 615 or newer |
| Size | 47898966 bytes (134652158 unpacked) |
| SHA-256 of the `.tpkg` | `0464a1f020937684b14c763d2ec9097d75e4f3b9c5b72509753a0b859963c3c2` |

## Commands it adds

| Command | Runs |
|---|---|
| `gcc` | `bin/gcc` |
| `cc` | `bin/gcc` |
| `g++` | `bin/g++` |
| `c++` | `bin/g++` |
| `cpp` | `bin/cpp` |
| `gcc-ar` | `bin/gcc-ar` |
| `gcc-nm` | `bin/gcc-nm` |
| `gcc-ranlib` | `bin/gcc-ranlib` |

## Download

The package file (`gcc-15.3.0-2.tpkg`) and the sources it was built from are the assets of the
[v15.3.0-2 release](https://github.com/Artfical/tpkg-gcc/releases/tag/v15.3.0-2).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `gcc-15.3.0.tar.xz`
- `gmp-6.2.1.tar.bz2`
- `mpfr-4.1.0.tar.bz2`
- `mpc-1.2.1.tar.gz`
- `isl-0.24.tar.bz2`

Check a download: `sha256sum gcc-15.3.0-2.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-3.0+ with GCC Runtime Library Exception. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
