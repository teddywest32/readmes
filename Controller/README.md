# jRAT Controller

## Features

- _should_ run on any system that supports Swing, full list [here](../README.md)
- Uses native system look and feel
- Easy to implement more types of clients, such as mobile phone users. Some work on Android devices has begun.


### Building

- Output as Java Archive ```.jar```
- Output as Mac OS X Application ```.app``` (using [JarToApp](https://github.com/redpois0n/JarToApp))
- Output as Windows Executable ```.exe```, requires .NET (using [jarbuilder](https://github.com/java-rat/jarbuilder))
- Export as
  - C/C++ Shellcode
  - C# Shellcode
  - Delphi Shellcode
  - Java Shellcode
  - Python Shellcode

## Arguments

Typed when running from terminal

```
$ java -jar Controller.jar --genkey --hidetitle --showhexkey ... ...
```

| Argument	  		| Description
| ---         		| :---
| --genkey			| Create new key file to default location (files/jrat.key)
| --hidetitle		| Main frame title is only "jRAT"
| --showhexkey		| Prints current key file to console
| -h, --headless	| Headless mode
| --nomenubar     | Doesn't use native OS X menubar

## Commands

Typed in the terminal

| Command	  		| Description
| ---         		| :---
| liststats			| Lists statistics for debugging purposes
| addstats			| Generates and adds random statistics for debugging purposes
| help		| Prints help for all available commands

## Dependencies

- [jrat-api](https://github.com/java-rat/jrat-api)
- [pluginlib](https://github.com/redpois0n/pluginlib)
- [graphslib](https://github.com/redpois0n/graphslib)
- [iconlib](https://github.com/redpois0n/iconlib)
- [oslib](https://github.com/redpois0n/oslib)
- [swing-terminal](https://github.com/redpois0n/swing-terminal)
- [pathtree](https://github.com/redpois0n/pathtree)
- [zkmlib](https://github.com/redpois0n/zkmlib)
