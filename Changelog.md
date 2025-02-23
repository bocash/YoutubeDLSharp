# YoutubeDLSharp Changelog

### v.1.0.0 (beta)
- **New**: Use yt-dlp instead of youtube-dl as default downloader.
- **New**: Methods for automatically downloading yt-dlp and FFmpeg.
- **New**: Addition of options, video & format data attributes for yt-dlp.
- **New**: MultiOption & MultiValue classes for options that can be set multiple times.
- **New**: Add .NET 6 as build target.
- **New**: Support extraction of chapter & comment information.
- **Changed**: Apply override options after setting other options in `YoutubeDL` methods.

### v.0.4.3 (2022-11)
- **Fixed**: Windows issues with non-ASCII chars in output.

### v.0.4.2 (2022-03)
- **Fixed**: Starting youtube-dl process blocks main thread

### v.0.4.1 (2022-01)
- **New:** Methods for adding, modifying & deleting custom options in `OptionSet`
- **Fixed:** Download state reporting in `YoutubeDLProcess`

### v.0.4.0 (2021-10)
- **New:** Support custom options
- **Fixed:** `start_time` & `end_time` properties in metadata

### v.0.3.1 (2021-06)
- **Fixed:** `MetadataType` in `VideoData`
- **Changed:** Include new changes in youtube-dl options

### v.0.3 (2020-09)
- **New:** Override options in OptionSet & YoutubeDL class.
- **New:** More download progress information (transfer rate, ...)
- **Fixed:** Converting option set to & from string.

### v.0.2 (2020-03)
- **New:** Option to capture output in YoutubeDL class.
- **New:** Added PythonPath to YoutubeDLProcess.
- **New:** Load configuration from file or string.
- **Fixed:** FormatData.FrameRate.

### v.0.1 (2020-01)
- First released version.
