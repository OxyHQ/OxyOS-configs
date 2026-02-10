# oxyos-configs

Various configuration files for use with [OxyOS](https://os.oxy.so).

## Building

To build a Debian package from your git clone (it is recommended to copy the folder first):

```bash
cd oxyos-configs
dpkg-buildpackage -us -uc
```

The resulting `.deb` package will be located one directory up.

---
Part of [OxyOS](https://os.oxy.so) | [GitHub](https://github.com/OxyHQ)
