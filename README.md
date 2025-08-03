ffmpeg-windows-build-helpers
============================

This helper script lets you cross compile a windows-based 32 or 64-bit version of ffmpeg.exe/mplayer/mp4box.exe, etc,  including their dependencies and libraries that they use.

**Cross-compiling from a Linux environment:**

Download the script by cloning this repository via git:

```sh
git clone https://github.com/ChakornK/audio-min-ffmpeg-win-crosscompile.git ffmpeg
cd ffmpeg
```

Now run the script:

```sh
./cross_compile_ffmpeg.sh
```

Answer the prompts.
It should end up with a working, statically-built ffmpeg.exe binary within the "`sandbox/*/ffmpeg_git`" director(ies).  You're done!
