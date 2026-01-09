# MP3Editor

A simple macOS app for editing ID3 tags on MP3 files.

## Features

- Drag & drop or browse to open MP3 files
- Edit common tags: title, artist, album, genre, year, track, disc, BPM
- Compilation flag support
- Save in place or as a copy
- Restore changes before saving

## Requirements

- macOS 13.0+
- Python 3

## Building

```bash
./build-app.sh
```

The build script creates a self-contained app bundle with its own Python virtual environment and dependencies. The built app will be at `MP3Editor.app` - drag it to your Applications folder.

## Download

Check the [Releases](../../releases) page for pre-built downloads.

## License

MIT
