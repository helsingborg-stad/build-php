# Municipio Build PHP

This file is designed to assist in building Municipio packages.

## Usage

To use the build script, run the following command:

```sh
wget https://build.municipio.tech/build.php -O build.php && php build.php
```

## Removable Files

The script includes a feature to remove files during the build process. This helps ensure that unwanted files do not reach production. To specify which files should be removed, add a `.distignore` file to your repository. The `.distignore` file uses a syntax similar to `.gitignore`.

## License

Licenced under MIT License. 

### Author
Sebastian Thulin