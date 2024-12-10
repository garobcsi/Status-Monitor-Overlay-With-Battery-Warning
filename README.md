# Status Monitor Overlay

## Project Diffrences

In the Overlay, in the micro sub overlay,
if you press `ZL+ZR+L+R` you can hide the overlay,
but if the battery goes over -8w,
the micro overlay will keep flashing red,
if the micro overlay is hidden and battery goes truh the -8w it will keep flasthing red.

## Building

```bash
git submodule update --init --recursive
make
```
