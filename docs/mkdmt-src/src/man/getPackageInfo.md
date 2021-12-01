
## Get information from a binary package

### Description

This function returns the compile-time information added to the
`DESCRIPTION` file in the package.

### Usage

    getPackageInfo(file)

### Arguments

| Argument | Description                             |
| -------- | --------------------------------------- |
| `file`   | the fully qualified path of the package |

### Value

A named vector with several components

### Note

This is an internal function, use `:::` to access it from outside the
internal package code.

### Author(s)

Dirk Eddelbuettel

