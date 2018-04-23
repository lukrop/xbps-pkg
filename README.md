# xbps-pkg

This is a small wrapper for XBPS with tab-completion. It provides a
simple interface inspired by FreeBSD's [pkg(8)].

[pkg(8)]: https://www.freebsd.org/cgi/man.cgi?query=pkg&sektion=8&manpath=FreeBSD+11.1-RELEASE+and+Ports

## Installation

```shell
curl -o /usr/local/bin/pkg https://raw.githubusercontent.com/lukrop/xbps-pkg/master/pkg
chmod +x /usr/local/bin/pkg
```

## Example usage

Install package *somepackage*
```shell
pkg install somepackage
```

Remove *somepackage*
```shell
pkg remove anotherpkg
```
Upgrade all packages
```shell
pkg upgrade
```

Find package to which /some/file belongs
```shell
pkg which /some/file
```

Hold *somepackage* at current version
```shell
pkg hold somepackage
```
See `pkg help` for more.

## Alternatives
- [xb](https://github.com/ernierasta/xb): simple wrapper with apk-like 
    interface.
- [vpm](https://github.com/netzverweigerer/vpm): another advanced, powerful 
    wrapper with colors!
- [octoxbps](https://github.com/aarnt/octoxbps): Qt5 GUI for XBPS.



