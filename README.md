# Arduino Silent night with led
I edited [Silent night code from arduino-songs](https://github.com/robsoncouto/arduino-songs/blob/master/silentnight/silentnight.ino) to use non-blocking [Neotimer](https://github.com/jrullan/neotimer) instead of the blocking `delay()` function.
This allowed me to also smoothly blink a led while playing the song.

## Tools used
+ VSCode
+ PlatformIO IDE