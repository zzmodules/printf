printf
======

> `printf(3)` bindings for ZZ

## Installation

Add this to your `zz.toml` file:

```toml
[dependencies]
printf = "*"

[repos]
printf = "git://github.com/zzmodules/printf"
```

## Usage

```c++
using printf::{ printf }
```

## API

`printf(format, ...)` and the following `printf` like functions are exported:

* `dprintf(fd, format, ...)`
* `fprintf(stream, format, ...)`
* `snprintf(str, format, ...)`
* `sprintf(str, size, format, ...)`
* `vdprint(fd, format, list)`
* `vfprintf(stream, format, list)`
* `vprintf(format, list)`
* `vsprintf(str, format, list)`
* `vsnprintf(str, size, format, list)`

## See Also

* https://linux.die.net/man/3/printf

## License

MIT
