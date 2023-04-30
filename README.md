# Markdown to PDF

This is a markdown to pdf wrapper for pandoc, its main purpose was to generate
a similar PDF to the one generated with [Obsidian](https://obsidian.md/) by
default.

## Example output

![pdf](https://user-images.githubusercontent.com/64109770/235328806-cb7bd0aa-0b7e-44d3-b162-aa50a482d3a7.gif)

## Dependencies

- [Pandoc](https://pandoc.org/)
- [Inter font](https://fonts.google.com/specimen/Inter)
- [Fira math font](https://github.com/firamath/firamath)

## Usage

```shell
$ ./md2pdf <input_file.md>
```

## Installation

If you want to install this script to your system just copy the executable to
`$HOME/.local/bin` to make it user wide or to `/usr/bin` to make it system-wide.

- User wide:
```shell
$ cp ./md2pdf $HOME/.local/bin
```

- System wide:
```shell
$ cp ./md2pdf /usr/bin
```
