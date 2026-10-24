# fileconv

A command-line file converter and compressor written in Rust, built as a
learning project.

Planned support:

- **Images** (pure Rust): png, jpg, webp, bmp, gif, with quality and resize compression
- **Audio/video** (via ffmpeg): mp3, mp4, mov
- **Documents** (via LibreOffice): doc/docx → pdf, plus PDF compression

```powershell
cargo run -- samples/photo.png out/photo.jpg
```

See [LEARNING.md](LEARNING.md) for the build roadmap.
