# Markdown to PDF

This is a markdown to pdf wrapper for [pandoc](https://pandoc.org/), its main
purpose is to generate a similar PDF to the one generated with
[Obsidian](https://obsidian.md/) by default.

## Example output

![pdf](https://user-images.githubusercontent.com/64109770/235328806-cb7bd0aa-0b7e-44d3-b162-aa50a482d3a7.gif)

## Dependencies

- [Pandoc](https://pandoc.org/)
- [Inter font](https://fonts.google.com/specimen/Inter)
- [Fira math font](https://github.com/firamath/firamath)

## Installation

If you want to install this script to your system, copy the executable to
`$HOME/.local/bin` or to `/usr/bin` if you want to install it user-wide or
system-wide respectively.

- User wide:
```shell
$ cp ./md2pdf $HOME/.local/bin
```

- System wide:
```shell
$ cp ./md2pdf /usr/bin
```

## Usage

```shell
$ md2pdf <input_file.md>
```
