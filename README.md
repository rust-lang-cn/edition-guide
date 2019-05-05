# The Rust Edition Guide

## Edition Guide 中文版 (Chinese)

> 本仓库不再维护，内容已移到新的仓库 [edition-guide-cn](https://github.com/rust-lang-cn/edition-guide-cn)：<https://github.com/rust-lang-cn/edition-guide-cn>，新仓库将持续跟进官方版本进行更新，欢迎大家 [Star 新仓库](https://github.com/rust-lang-cn/edition-guide-cn)。

[![Build Status](https://travis-ci.org/rust-lang-nursery/edition-guide.svg?branch=master)](https://travis-ci.org/rust-lang-nursery/edition-guide)

This book explains the concept of "editions", major new eras in [Rust]'s
development. You can [read the book
online](https://rust-lang-nursery.github.io/edition-guide/).

[Rust]: https://www.rust-lang.org/

## License

The Edition Guide is dual licensed under `MIT`/`Apache2`, just like Rust itself.
See the `LICENSE-*` files in this repository for more details.

## Building locally

You can also build the book and read it locally if you'd like.

### Requirements

Building the book requires [mdBook]. To get it:

[mdBook]: https://github.com/azerupi/mdBook

```bash
$ cargo install mdbook
```

### Building

To build the book, do this:

```bash
$ mdbook build
```

The output will be in the `book` subdirectory. To check it out, open it in
your web browser.

_Firefox:_

```shell
$ firefox book/index.html                       # Linux
$ open -a "Firefox" book/index.html             # OS X
$ Start-Process "firefox.exe" .\book\index.html # Windows (PowerShell)
$ start firefox.exe .\book\index.html           # Windows (Cmd)
```

_Chrome:_

```shell
$ google-chrome book/index.html                 # Linux
$ open -a "Google Chrome" book/index.html       # OS X
$ Start-Process "chrome.exe" .\book\index.html  # Windows (PowerShell)
$ start chrome.exe .\book\index.html            # Windows (Cmd)
```

To run the tests:

```bash
$ mdbook test
```
