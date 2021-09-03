Video Trim Tool
===============

Trim video files to the exact portion desired, discarding the useless content and saving space.

Use `video_trim_tool.py -t path-to-dir-with-video-files` to generate a template file. Edit with start and stop time (in seconds) and then run `video_trim_tool.py -i path-to-videotrim.txt`.

The `videotrim.txt` file should look something like

```
# autogenerated file
2021-08-23-21-15-19.MP4 29 67
2021-08-23-22-18-36.MP4 11 65
2021-08-23-22-00-52.MP4 17 67
2021-08-23-21-36-52.MP4 17 70
2021-08-23-22-21-08.MP4 13 37
2021-08-23-22-13-33.MP4 14 62
2021-08-23-22-16-12.MP4 13 62
2021-08-23-22-07-19.MP4 16 36 / 60 74
```

The `/` is used to create multiple splits from a single source
