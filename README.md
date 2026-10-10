# oxyos-configs

Various configuration files for use with [OxyOS](https://oxy.so/os).

## Building

To build a Debian package from your git clone (it is recommended to copy the folder first):

```bash
cd oxyos-configs
dpkg-buildpackage -us -uc
```

The resulting `.deb` package will be located one directory up.

---
Part of [OxyOS](https://oxy.so/os) | [GitHub](https://github.com/OxyHQ)
