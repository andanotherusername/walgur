# walgur
:computer: Set your desktop background from randomly picked Imgur links! :framed_picture:

<img src="https://goreportcard.com/badge/github.com/M4cs/walgur"> <a href="https://github.com/M4cs/walgur/stargazers"> <img alt="GitHub stars" src="https://img.shields.io/github/stars/M4cs/walgur"></a> <a href="https://github.com/M4cs/walgur/issues"> <img alt="GitHub issues" src="https://img.shields.io/github/issues/M4cs/walgur"></a>

<p align="center">
  <img src="https://raw.githubusercontent.com/M4cs/walgur/master/preview.gif">
  
</p>

## Installation

```bash
go get github.com/M4cs/walgur
go install github.com/M4cs/walgur
```

or build from source

```bash
git clone github.com/M4cs/walgur
cd walgur
go build
# Move the walgur binary to your $PATH
```

## Usage

```
walgur -u <imgur URL> [-s]
```

`-u <url>` - URL to grab from

`-s` - Show Background File Path

#### Supports:

- Albums
- Tags
- Subreddits
- Galleries

This will randomly pick an image from said URL and set it as your wallpaper.
