Moo -- a file renamer for the web
==============================

## SYNOPSIS

This is a tool to help you quickly rename whatever files to a web safe format.

Much more info available via `moo --help` once it's installed.

## Install

Make sure you have npm installed. npm is bundled with [node](http://nodejs.org/download/).

### Windows Computers

In command prompt with administrator privileges, type:

```sh
npm install -g moo-rename
```

### Apple Macintosh Computers

Open bash or terminal, type:

```sh
npm install -g moo-rename
```

## Usage

Rename PDF files in 'pdfs' folder.
```sh
moo "pdfs\*.pdf"
```

Rename all files in 'pdfs' folder.
```sh
moo "pdfs\*"
```

Rename all files in current folder.
```sh
moo "."
```

Rename all text files in current folder.
```sh
moo "*.txt"
```

Rename all files in 'pdfs' and all its sub-directories.
```sh
moo "pdfs\**\*"
```

Rename all PDFs in 'pdfs' and all its sub-directories.
```sh
moo "pdfs\**\*"
```
