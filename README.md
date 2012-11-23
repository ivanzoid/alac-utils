# ALAC (Apple Lossless Audio Codec) command-line utils

## cue2alac

Converts ape+cue, wv+cue, flac+cue to separate m4a (ALAC) tracks.

#### Dependencies:
Install the following packages: `ffmpeg flac shntool cuetools`

#### Usage:
`cue2alac <cuefile>`
Will convert cuesheet+file to .m4a tracks in current directory.

## flac2alac

Converts flac track to alac track.

#### Dependencies:
Install the following packages: `ffmpeg flac`

#### Usage

`flac2alac <flacfile>`
