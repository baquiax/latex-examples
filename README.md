LaTeX
=====

## Installation

### Linux

This example repo was made for GNU/Linux OSs.

Specifically for Ubuntu you  need to have installed this dependencies:
```
apt-get install texlive texlive-base texlive-latex-base texlive-latex-recommended texlive-latex-extra
```

### Optional

If you want to format your code you can have installed `latexindent`. This project is basically a `Perl` script.

This is the repo [https://github.com/cmhughes/latexindent.pl](https://github.com/cmhughes/latexindent.pl)

Install this in your local environment isn't conventional as you expected, but is easy to do.

Fromt the repo we need only some files (all are interesting but for indent, just some of them are needed)

Download them with this simple instructions:
```
wget -P latexindent/ https://raw.githubusercontent.com/cmhughes/latexindent.pl/master/latexindent.pl

wget -P latexindent/  https://raw.githubusercontent.com/cmhughes/latexindent.pl/master/defaultSettings.yaml

wget -P latexindent/path-helper-files/ https://raw.githubusercontent.com/cmhughes/latexindent.pl/master/path-helper-files/CMakeLists.txt

wget -P latexindent/path-helper-files/ https://raw.githubusercontent.com/cmhughes/latexindent.pl/master/path-helper-files/cmake_uninstall.cmake.in
```



