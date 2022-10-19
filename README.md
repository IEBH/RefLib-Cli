Reflib-CLI
==========
Command line interface for [Reflib](https://github.com/hash-bang/Reflib-Node).


Usage
-----
```
Usage: reflib [file...]

Options:
  -c, --count               Dont output refs, just output the count (sets `-o
                            count`)
  -j, --json                Output valid JSON (sets `-o json`)
  -x, --xml                 Output EndNote XML file (sets `-o endnotexml`)
  -o, --output [mode]       Output file format (any reflib format + inspect,
                            json, count) (default: "json")
  -f, --output-file [path]  Output data into a file instead of STDOUT (sets -o
                            to a mode matching the filetype if possible)
  -v, --verbose             Be verbose (also prints a running total if -c is
                            specified)
  --no-color                Force disable color
  -h, --help                display help for command
```
