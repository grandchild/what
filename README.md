# `what` — An enhanced `which` for Archlinux


### Usage Examples
```shell
$ what which
/usr/bin/which: which 2.21-6 "A utility to show the full path of commands"

$ what convert
/usr/bin/convert: imagemagick 7.1.1.43-1 "An image viewing/manipulation program"

$ what ldd
/usr/bin/ldd: glibc 2.41+r2+g0a7c7a3e283a-1 "GNU C Library"
```

Errors:

```shell
$ what what
error: No package owns /home/me/bin/what

$ what binary-that-does-not-exist
binary-that-does-not-exist not in $PATH
```


### Installation

- [Read & save](https://raw.githubusercontent.com/grandchild/what/main/what)
- `chmod +x what`


### License

[![License](https://img.shields.io/github/license/grandchild/what.svg)](
https://creativecommons.org/publicdomain/zero/1.0/)

You may use this code without attribution, that is without mentioning where it's from or
who wrote it. I would actually prefer if you didn't mention me. You may even claim it's
your own.
