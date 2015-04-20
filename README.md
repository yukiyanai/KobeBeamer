# KobeBeamer


# LaTeX Beamer Theme for Kobe University

**Yuki Yanai**, Assistant Professor, *Graduate School of Law, Kobe University*

This is an *unofficial* Beamer theme for Kobe University.

![Example](examples/example-BeamerKobe.jpg)

## Installation

Download this direcotry by clicking **Download ZIP** button on the right.

Unzip the downloaded file, and move it to the directory where you keep LaTeX style files or Beamer theme files. In my environment, it is:

```
~/Library/texmf/tex/latex/beamer/
```

A Mac user's default directory should be something like:

```
/usr/local/texlive/2014/texmf/tex/latex/
```

A Windows user's default should be something like:

```
C:\localtexmf\tex\latex\beamer\themes\
```

Once you put the KobeBeamer folder in the appropriate directory, type in the terminal:

```
sudo mktexlsr
```

## Usage

Add the following line to the preamble:

```
\usetheme{Kobe}
```

Currently, three options are available.

1. nonav: suppress the navgaition bar
2. nologo: does not show the university logo mark
3. simplefoot: only the slide number is displayed in footer

To use these options, write in the preamble

```
\usetheme[nonav]{Kobe}
```

or

```
\usetheme[nologo]{Kobe}
```

or

```
\usetheme[nonav,simplefoot]{Kobe}
```
etc.

Please use **nologo** option if you have not obtained the logo files yourself from the [Kobe University's official website](http://www.kobe-u.ac.jp) (see **Kobe University Logo** below).


## Color Theme

At the moment, two color themes are available.

#### Theme 1: uribo

This color theme is distributed as [beamercolorthemeuribo.sty](beamercolorthemeuribo.sty).
It uses four officially defined school colors: Kobe-Brick (RGB: 196, 0, 0), Kobe-Green (23, 131, 46), Kobe-Blue (14, 47, 146), and Kobe-Gray (77,77, 77).

This is the default color theme for Kobe Beamer.

To use this color theme with another Beamer theme, write in the preamble:

```
\usecolortheme{uribo}  
```

#### Theme 2: uriboBlack

This color theme is distributed as [beamercolorthemeuriboBlack.sty](beamercolorthemeuriboBlack.sty).

To use this color theme, write in the preamble:

```
\usecolortheme{uriboBlack}  
```


## Kobe Univeristy Logo

Since I am not allowed to distribute the official logos of Kobe University, the logo files are not available here.

You must either obtain the logos from the official website of the university or use **nologo** option (see **Usage** above).


#### Getting the logos

To obtain the logos, you need to connect to the Kobe University's network system. You can connect to the University's network on campus or via VPN.

1. Go to [the download page](http://www.kobe-u.ac.jp/info/outline/resources/logo2.html) in the Kobe Univeristy's official website.
2. Download the logo (A) with the transparent background （透明背景）[[direct link](http://www.ofc.kobe-u.ac.jp/kouhoushitsu/logo_app/3_Logo_png/A_C.png)] and save it as **kobe-logo.png** in the **logo** folder inside KobeBeamer folder.
3. Download the logo (J) with the transparent background （透明背景）[[direct link](http://www.ofc.kobe-u.ac.jp/kouhoushitsu/logo_app/3_Logo_png/J_C.png)] and save it as **kobe-logo-wide.png** in the **logo** folder inside KobeBeamer folder.


## Examples

You can find some examples in [examples](examples) folder.
