<h1 align=center>
tv-cli
</h1>
</p>

<h3 align="center">
A cli to browse and watch live TV. This tool scrapes the site <a href="https://ustvgo.tv">ustvgo.</a>
</h3>
	
## Table of Contents

- [Install](#Install)
  - [Linux](#Linux)
  - [MacOS](#MacOS)
- [Uninstall](#Uninstall)
- [Dependencies](#Dependencies)
- [Disclaimer](./disclaimer.md)

## Install

### Linux

Install dependencies [(See below)](#Dependencies)

```sh
git clone "https://github.com/Spaxly/tv-cli.git" && cd ./tv-cli
sudo cp ./tv-cli /usr/local/bin
cd .. && rm -rf "./tv-cli"
```
*Also note that mpv installed through flatpak is not compatible*

### MacOS

Install dependencies [(See below)](#Dependencies)

Install [HomeBrew](https://docs.brew.sh/Installation) if not installed.

```sh
git clone "https://github.com/Spaxly/tv-cli.git" && cd ./tv-cli
cp ./tv-cli "$(brew --prefix)"/bin 
cd .. && rm -rf ./tv-cli
```

*To install (with Homebrew) the dependencies required on Mac OS, you can run:* 

```sh
brew install ffmpeg mpv python git
``` 
## Uninstall

* Linux:  
```sh
sudo rm "/usr/local/bin/tv-cli"
```
* Mac:  
```sh
rm "$(brew --prefix)/bin/tv-cli"
```

## Dependencies

- python
- pip
- git
- fzf
- fzf.py (to install, run this command: `pip install git+https://www.github.com/justfoolingaround/fzf.py`)
