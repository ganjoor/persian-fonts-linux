Persian fonts for Linux
=======================

This script downloads and installs Persian fonts for Linux.

```
usage: ./farsifont.sh
```

## Available fonts


```
 1) Vazir          11) XBNilufar       21) XBSols      31) Samim
 2) FarsiFonts     12) XBKhoramshahr   22) XBTitr      32) Shabnam
 3) BFonts         13) XBKayhan        23) XBTabriz    33) Sahel
 4) IranianSans    14) XBYaghout       24) XBTraffic   34) VazirCode
 5) IranNastaliq   15) XBRiyaz         25) XBVahid     35) Tanha
 6) FPF            16) XBRoya          26) XBVosta     36) Nahid
 7) Lalezar        17) XBShafigh       27) XBYermook   37) Parastoo
 8) NotoNaskh      18) XBShafighKurd   28) XBYas	    
 9) NotoKufi       19) XBShafighUzbek  29) XBZiba	    
10) XBZar          20) XBShiraz        30) Tahoma
```

```
38) All
39) Quit
```

## Getting started

In the TeX file, include the following commands.

```
\usepackage{xepersian}
\usepackage{fontspec}
\settextfont[Scale=1]{IranNastaliq}
\setlatintextfont[Scale=1]{TeX Gyre Termes}
```

Compile the TeX file using `xelatex`.

```
xelatex <TeX file>
```
