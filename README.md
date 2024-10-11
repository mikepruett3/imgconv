imgconv
=======

Convert and compress JPEG and PNG images from the command line. **(WIP)**

## Install from source

```bash
go install github.com/mikepruett3/imgconv@latest
```

### Windows Context-Menu Integration

Provided a registry script that will create `Convert to...` items in the Right-Click context menu. Only for .PNG, .JPG, and .JPEG files for now.

You can import the `imgconv.reg` file by either double-clicking it, or

```powershell
reg import imgconv.reg
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
