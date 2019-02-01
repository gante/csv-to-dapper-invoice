## Simple CSV to good-looking LaTeX invoice

A slightly dumbed-down version of the [Dapper Invoice](https://github.com/mkropat/dapper-invoice ),
but with CSV loading capabilities.

![Example Screenshot](http://i.imgur.com/q78jtGu.png)

### Generating an Invoice

#### Filling the CSV

Fill it in as any .csv file. Be careful with special characters like \# within
the .csv, as they will generate an error if not input with the appropriate codification (e.g. \\\#)

#### Creating the Invoice

Open the .tex, edit the basic information, and compile (with XeLaTeX or LuaLaTeX).

### Documentation

See [example.tex](example.tex) and [dapper-invoice.cls](dapper-invoice.cls) for details.


### Licensing

The code I have written I release under the MIT license (as the original repo)

