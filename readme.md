# Markdown-toc
Generate index and toc for markdown files.

## Usage
```
usage: markdown_toc.py [-h] [-i INDEX_DEPTH] [-t TOC_DEPTH] [--no-toc] [--no-index]
                       input_file [output_file]

positional arguments:
  input_file            input file name.
  output_file           output file name.

optional arguments:
  -h, --help            show this help message and exit
  -i INDEX_DEPTH, --index-depth INDEX_DEPTH
                        max index depth, default 3
  -t TOC_DEPTH, --toc-depth TOC_DEPTH
                        max toc depth, default 3
  --no-toc              don't create content
  --no-index            don't create index
```