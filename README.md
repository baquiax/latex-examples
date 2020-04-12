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

You need first to clone the git repo in your local machine.

Use this instruction to do that:
```
wget  -c  https://github.com/cmhughes/latexindent.pl/archive/V3.8.tar.gz -O - | tar -xzv
```

Now you need to compile and install the `latexindent`, bur before you need to validate if the compiler is installe on your machine:
```
sudo apt-get install cmake
sudo apt-get install build-essential
cpan YAML::Tiny
cpan File::HomeDir
cpan Unicode::GCString
cpan --installdeps Log::Log4perl
cpan --force Log::Log4perl
cpan Log::Dispatch::File
```

Ok, all dependencies are ready. So execute the below commands:

```
mkdir -p latexindent.pl-3.8/build && cd latexindent.pl-3.8/build
cmake ../path-helper-files
make install
```


