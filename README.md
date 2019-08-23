# Husarion NoVSCode
This repository contains the sdk unpackaged from Husarion’s VSCode extension. None of this code is mine; it is redistributed using the original MIT License for the project at `sdk/LICENSE`.

Currently, the only provided and documented build options are for Husarion are 1. Their Web IDE or 2. Their VSCode extension. This repository allows you to build offline using neither of these tools.

## Example Compilation

```
$ cmake -DBOARD_TYPE=CORE2 -DHFRAMEWORK_PATH=sdk/ -S . -B build/
$ cd build && make
```
