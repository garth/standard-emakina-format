# standard-emakina-format

  This is a fork of [standard-format](https://github.com/maxogden/standard-format) same concept but for emakina.

## Installation

  Install with npm

    $ npm install standard-emakina-format

## Example Usage

  Output all formatted javascript in a directory and subdirectories to stdout

    $ standard-emakina-format

  Format all javascript files, overwriting them into standard format

    $ standard-emakina-format -w

  Format javascript over stdin

    $ standard-emakina-format < file.js > formatted-file.js

  Format and overwrite specific files

    $ standard-emakina-format -w file1.js file2.js
