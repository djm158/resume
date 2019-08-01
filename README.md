[![Build Status](https://travis-ci.com/djm158/resume.svg?branch=master)](https://travis-ci.com/djm158/resume)
# LaTeX resume

template from [LaTeX Templates](http://www.latextemplates.com/template/medium-length-professional-cv)
original author: [Trey Hunner](http://treyhunner.com/)

## Build

You can clone this repository and use my resume as a template. If you choose not to clone this repository and instead use the original from latextemplates.com, it is important the file `resume.cls` is in the same directory as your `.tex` file.

```sh
$ git clone https://github.com/djm158/resume
```

### Linux

```sh
$ sudo apt-get install texlive
$ xelatex danmcgrathresume.tex
```

### Windows

1. Install [MiKTeX](https://miktex.org/)
2. Open TeXworks front end

  ![MiKTex console screenshot](https://github.com/djm158/resume/blob/master/images/miktex_texworks.png)

3. Set to XeLaTeX mode 

  ![MiKTeX texworks xelatex screenshot](https://github.com/djm158/resume/blob/master/images/miktex_xelatex.png)

### Mac

I assume [Homebrew](https://brew.sh/) can install a LaTeX distribution like tex live. Sorry, not a mac person :blush:

#### note

I'm not sure why I use tex live on linux and MiKTeX on Windows. Truth be told, at the time of writing this document, I mainly live in Windows and use WSL for my linuxy needs.
