# how to include
This package expands tex's listings to highlight Rust keywords.

Copy content to your .tex file

If you want to use by default of listings, you should mv these files to /path/to/listings and overwrite listings.cfg like below.

```tex
\def\lstlanguagefiles
    {lstlang0.sty,lstlang1.sty,lstlang2.sty,lstlang3.sty,lstlang4.sty} % add lstlang4.sty!
```
