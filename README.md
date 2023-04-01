# DateTime Printer

This project was created to demonstrate how to package Python projects using Poetry.

## Getting Started

To get started, you need to install Poetry:

```
$ pip install -U pip
$ pip install poetry
```

To authenticate with PyPI:


```
$  python -m poetry config http-basic.pypi <USERNAME> <PASSWORD>
```

## Building the Package

To build the package, run the following command in the project root directory:

```
$ python -m poetry build
```

This command will create a source distribution and a wheel distribution of the package in the dist/ directory:

```
Building datetime_printer (1.0.0)
  - Building sdist
  - Built datetime_printer-1.0.0.tar.gz
  - Building wheel
  - Built datetime_printer-1.0.0-py3-none-any.whl
```

## Publishing the Package

To publish the package, run the following command:


```
$ python -m poetry publish
```

This command will upload the package to PyPI:

```
Publishing datetime_printer (1.0.0) to PyPI
 - Uploading datetime_printer-1.0.0-py3-none-any.whl 100%
 - Uploading datetime_printer-1.0.0.tar.gz 100%
```

## Installing the Package

To install the package, run the following command:

```
$ pip install datetime-printer
```

## Usage

To use the package, run the following command:

```
$ python -m datetime_printer.main
```

This will print the current date and time:

```
Current date and time:  2023-04-01 03:02:50.746358
```
