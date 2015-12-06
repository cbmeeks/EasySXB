EasySXB
=======

![Screenshot](https://raw.githubusercontent.com/Mortis69/EasySXB/master/screenshots/screenshot.png)

EasySXB is a terminal/program loader designed for use with Western Design Center's SXB line of development boards.

Program files (in HEX format) can be uploaded through the terminal interface. (This can be slow for larger programs.)

Must be run under Linux with the ```sudo``` command. (Windows support coming soon.)

## Build it from source
```$ git clone https://github.com/Mortis69/EasySXB.git```

```$ cd EasySXB```

Uncompress the FLTK-1.3.3 source package here.

The Makefile supports ```linux``` and ```mingw``` cross-compiler targets.
(Edit the Makefile to choose.)

```$ make fltk```

```$ make```

## Dependencies

### Libraries

 * FLTK-1.3.3
 * libxft-dev (required for font rendering)

