# General Relativity Course Notes
I am organizing Yidun Wan's lecture notes into a typesetted latex document.
It will take a lot of time to draw tikzpictures and insert equations,
so I will only keep maintaining this impulsive and useless work when I have time.

## Templates and other tex files
The template is borrowed from [The Legrand Orange Book](http://www.latextemplates.com/template/the-legrand-orange-book), and I have modified the distance of chapter headings. And other custom settings are stored in `custom_style.tex`

## Build
Building the `.tex` files requires *lualatex* for custom fonts (i.e. Comic Sans) and `-shell-escape` option for `\includestandalone{}` macro (for auto-compling and include external tikz files).

```
lualatex -shell-escape Review.tex
```

