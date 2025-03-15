# plutovg-d
Tiny 2D vector graphics library

This is an example project for D binding through ImportC

## Build
Currently the code assumes that library files are put into `lib` folder.
For usage you will need to build original library first and put `include` folder and library object file (currently it is `libpluto.a` into `lib` folder).
After that just run:
```bash
dub build
```

# References
[Original C library](https://github.com/sammycage/plutovg)
