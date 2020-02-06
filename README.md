# Docusema

[![Build Status](https://travis-ci.com/MilesChou/docusema.svg?branch=master)](https://travis-ci.com/MilesChou/docusema)
[![codecov](https://codecov.io/gh/MilesChou/docusema/branch/master/graph/badge.svg)](https://codecov.io/gh/MilesChou/docusema)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/416d2087f50144e5be348825ff912936)](https://www.codacy.com/manual/MilesChou/docusema)

The Schema docs generator for Laravel project

## Usage

Download the [PHAR](https://github.com/MilesChou/docusema/releases) file, and run the following command in your Laravel project:

```
php docusema.phar
```

It will generate database schema document in `generated` directory.

## Example

Here is example [SQL](/examples/examples.sql), import MySQL and run following command:

```
php bin/docusema.php --config-file=tests/Fixtures/database.php --connection=examples --output-dir=examples
```

It will generate this [Markdown document](/examples/users.md).
