# Stacc CLI

This repository is being used to hold the Stacc CLI [releases](https://github.com/stacc/cli/releases).

## Installation

* [Snap](#using-snap-linux)
* [Homebrew](#using-homebrew-macos--linux)
* [Scoop](#using-scoop-windows)
* [From terminal](#from-terminal)
* [Direct download](#direct-download)

### Using snap (Linux)

Simply run the following command

```
$ snap install stacc
```

### Using homebrew (MacOS / Linux)

First add the repository with

```
$ brew tap stacc/tap
```

Then install the CLI with

```
$ brew install stacc
```

### Using scoop (Windows)

First add the repository with

```
$ scoop bucket add stacc https://github.com/stacc/cli
```

Then install the CLI with

```
$ scoop install stacc
```

### From terminal

MacOS and Linux users

```
$ curl -s https://raw.githubusercontent.com/stacc/cli/main/install.sh | bash -s --
```

Windows users

```
$ curl -LSs https://raw.githubusercontent.com/stacc/cli/main/install.bat -o %TEMP%\stacc-install.bat && CMD /C %TEMP%\stacc-install.bat && del %TEMP%\stacc-install.bat
```

### Direct download

Download the latest release [here](https://github.com/stacc/cli/releases/latest).
