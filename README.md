# FFmpegKit SPM

> [!WARNING]  
> Since the upstream [FFmpegKit](https://github.com/arthenica/ffmpeg-kit) project has been retired, this one has been retired as well.

This is a Swift Package Manager compatible version of [FFmpegKit](https://github.com/arthenica/ffmpeg-kit). 
It distributes and bundles the ffmpeg-kit-https version for iOS, macOS and tvOS as a single xcframework. 

### Installation
Add this repo to as a Swift Package dependency to your project
```
[https://github.com/tylerjonesio/ffmpeg-kit-spm](https://github.com/sami79031/ffmpeg-kit-spm-mx)
```

If using this in a swift package, add this repo as a dependency.
```
.package(url: "https://github.com/sami79031/ffmpeg-kit-spm-mx/", .upToNextMajor(from: "5.1.0"))
```

### Usage

To get started, import this library: `import ffmpegkit` \
_If you are wanting to use the FFmpeg libav c libraries directly: `import FFmpeg`_

See the [FFmpegKit wiki](https://github.com/arthenica/ffmpeg-kit/tree/main/apple#3-using) for more info on integration and usage for FFmpeg. \
_For using FFmpeg directly, see the [FFmpeg documentation](https://trac.ffmpeg.org/wiki/Using%20libav*) here_

### Building
If you would like to build your own xcframework binaries run the `build.sh` script on a macOS machine. 
