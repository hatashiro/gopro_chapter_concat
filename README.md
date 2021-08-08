# `gopro_chapter_concat`

A simple script to concat GoPro chapters.

## How to use

```bash
./gopro_chapter_concat --help

# Example usages
./gopro_chapter_concat GH010001.MP4 GH020001.MP4 GH030001.MP4
./gopro_chapter_concat *.MP4
./gopro_chapter_concat -o neko.mp4 *.MP4
```

## Caveat

Some metadata may not be preserved.

## Credit

The following Reddit posts should be given credits.

- [Merging raw GPMD as metadata stream : ffmpeg](https://www.reddit.com/r/ffmpeg/comments/8qosoj/merging_raw_gpmd_as_metadata_stream/)
- [Merge Chapters and Retail Metadata : gopro](https://www.reddit.com/r/gopro/comments/k0j8p3/merge_chapters_and_retail_metadata/)

## License

[Apache 2.0](LICENSE)
