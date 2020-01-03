# GifRecorder
Bash script to record your screen in a gif on Ubuntu

![Animation](http://erickzanardo.github.io/gifrecorder/animation.gif)

## Usage

Starts the recording

```shell
gifrecorder record
```

Stops de recording

```shell
gifrecorder stop
```

Your animation will be saved in your `$HOME` folder, under the name of `gifrecord_${TIMESTAMP}.gif`.

## Dependencies

- scrot
- imagemagick
- notify-send (optional)
