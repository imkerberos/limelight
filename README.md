## Limelight

Simple C99 sample showing how to create a border that will follow the focused window on macOS.

Requires access to the accessibility API. Supports macOS High Sierra and newer.

```sh
# add the following to the end of your yabairc to have it launch automatically when yabai starts.
# substitute the path to the limelight binary in the 2nd line below.

killall limelight &> /dev/null
/path/to/bin/limelight &> /dev/null &
```

### Build

Requires xcode command line tools

```sh
# simply clone repo and run make
  make
```
