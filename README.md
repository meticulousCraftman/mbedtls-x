# mbedTLS library for Mongoose OS

This library is optimized by Cesanta for lower memory usage.

It also includes support for ATECC508 crypto chip.

# Building a binary library

To use this library in any Mongoose OS app, we first need to build a binary library.

```
$ mos build --local --platform stm32 --verbose --clean --repo "mongoose-os-x" --build-image "meticulouscraftman/stm32-build:r19" 
```