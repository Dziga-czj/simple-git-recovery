# Simple .git recovery
A simple tool that recovers some files with the objects found in the .git file.
Uses the `git cat-file` command to get the data back, and then guesses the extension with `exiftool`.


Some warnings are expected.

## Requirements
Uses `exiftool`


## usage 
put this file inside a directory with a .git directory

```
./git-recover [options]
    -O override output directory
```
