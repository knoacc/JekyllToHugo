# Jekyll To Hugo

This is a small script for converting [jekyll](jekyllrb.com) posts to [hugo](gohugo.io)

It requires python and should work on all unix like systems, possibly also on windows machines
however it's only been tested on debian using python 2.7


## Limitations

It currently does not handle static resources such as images and scripts, these will have to be moved to
there correct locations manually.
As for jekyll specific codes it only handles {% Highlighting %} converting it into the hugo format

# Usage

jekyllToHugo.py [-h] [-o OUTPUT] [-v] source

Options

positional arguments:
  source                Path to folder containing jekyll posts

optional arguments:
  -h, --help            show this help message and exit
  -o OUTPUT, --output OUTPUT
                        Path to output folder, will be created if it does not
                        exist. Defaults to content
  -v, --verbose         Print extra logging output
