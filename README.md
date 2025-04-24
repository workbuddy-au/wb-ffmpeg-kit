# FFmpegKit 

`FFmpegKit` is a collection of tools to use `FFmpeg`<sup>1</sup> in `Android`, `iOS`, `Linux`, `macOS`, `tvOS`, `Flutter` and `React Native` applications.

It includes scripts to build `FFmpeg` native libraries, a wrapper library to run `FFmpeg`/`FFprobe` commands in
 applications and 8 prebuilt binary packages available at [Github](https://github.com/arthenica/ffmpeg-kit/releases),
 [Maven Central](https://search.maven.org), [CocoaPods](https://cocoapods.org), [pub](https://pub.dev) and [npm](https://www.npmjs.com).

This version is using full-gpl binaries by default.

### 14. License

`FFmpegKit` library alone is licensed under the `LGPL v3.0`.

`FFmpegKit` bundles (`.aar` archives, `frameworks`, `xcframeworks`), which include both  `FFmpegKit` and `FFmpeg`
libraries, are also licensed under the `LGPL v3.0`. However, if the source code is built using the optional
`--enable-gpl` flag or prebuilt binaries with `-gpl` postfix are used, then `FFmpegKit` bundles become subject to the
`GPL v3.0`. Because, `FFmpeg` is licensed under the `GPL v3.0` in those bundles. And that makes the whole bundle
effectively subject to the `GPL v3.0`.

`FFmpegKit` build scripts always configure `FFmpeg` with `--enable-version3` option. And never enable non-free
libraries. Thus, `FFmpeg` libraries created by `FFmpegKit` are licensed under the `LGPL v3.0` by default. Only when
`--enable-gpl` is provided they become subject to `GPL v3.0`. That is how prebuilt binaries with `-gpl` postfix are
compiled.

Refer to [Licenses](https://github.com/arthenica/ffmpeg-kit/wiki/Licenses) to see the licenses of all libraries.
[Trademark](https://github.com/arthenica/ffmpeg-kit/wiki/Trademark) lists the trademarks used in the `FFmpegKit`
documentation.

### 15. Patents

It is not clearly explained in their documentation, but it is believed that `FFmpeg`, `kvazaar`, `x264` and `x265`
include algorithms which are subject to software patents. If you live in a country where software algorithms are
patentable then you'll probably need to pay royalty fees to patent holders. We are not lawyers though, so we recommend
that you seek legal advice first. See [FFmpeg Patent Mini-FAQ](https://ffmpeg.org/legal.html).

`openh264` clearly states that it uses patented algorithms. Therefore, if you build `ffmpeg-kit` with `openh264` and
distribute that library, then you are subject to pay MPEG LA licensing fees. Refer to
[OpenH264 FAQ](https://www.openh264.org/faq.html) page for the details.

### 16. Trademarks

<sup>1</sup> `FFmpeg` is a trademark of [Fabrice Bellard](http://www.bellard.org/). `FFmpegKit` is an independent project and not affiliated with the `FFmpeg` trademark holder.

### 17. Contributing

See our [CONTRIBUTING](CONTRIBUTING.md) guide.

### 18. See Also

- [FFmpeg API Documentation](https://ffmpeg.org/doxygen/4.0/index.html)
- [FFmpeg Wiki](https://trac.ffmpeg.org/wiki/WikiStart)
- [FFmpeg External Library Licenses](https://www.ffmpeg.org/doxygen/4.0/md_LICENSE.html)
# wb-ffmpeg-kit
