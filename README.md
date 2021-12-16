# remark-template

My personal [remark](https://remarkjs.com) template.

## How-to

From the presentation directory:

```sh
python3 -m http.server
```

> Don't forget to update `<title>` tag in `index.html` and add an appropriate `favicon.png`

## PDF Export

Export via decktape works fine:

```sh
decktape remark <url> <filename.pdf> --chrome-arg=--disable-web-security --size 320x240
```

https://github.com/gnab/remark/wiki/Printing---Export-to-PDF

## References
- [The remark GitHub project](https://github.com/gnab/remark)
