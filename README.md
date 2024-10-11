imgconv
=======

Convert and compress JPEG and PNG images from the command line. **(WIP)**

## Install from source

```bash
go install github.com/mikepruett3/imgconv@latest
```

## Usage

```bash
imgconv test.png 75
```

Converts test.png to a jpeg with quality of 75.

```bash
imgconv test.jpg
```

Converts test.jpg to a png.

## Roadmap

- [ ] Flags for compression - no conversion
- [ ] Compression of png
