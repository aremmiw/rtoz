# rtoz
POSIX shell script to batch convert RAR/CBR, 7z/CB7, TAR/CBT, etc into ZIP/CBZ.  
This is useful for eReader software like KOReader which doesn't support RAR.

Archive formats that bsdtar/libarchive supports should work.

## usage
By default ZIP/CBZs are stored into the current directory. This can be changed with the `-o` option.

```
rtoz - Convert RAR/CBR and other archive formats into ZIP/CBZ

Dependencies: bsdtar

Usage: bsd-tar [OPTION]... FILE...
 -h		Show this help
 -o DIRECTORY	Save ZIP/CBZ files to this location. Defaults to '.'
```

## dependencies
* bsdtar (libarchive)
