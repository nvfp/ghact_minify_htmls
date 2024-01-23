Minify all your HTML files using [minify-html](https://github.com/kangax/html-minifier) tool with prechosen params (aiming for maximum compression). This is a pre-build/post-build tool for a website building project.

## usage

```yml
- uses: nvfp/ghact_minify_htmls@...  # use the latest version is recommended.
  with:
    folder: ./_site  # will minify all HTML files recursively inside this folder (use rel. path, relative to root)
```

Please read the file `action.yml` to learn more.

## notes

- make sure all the html files have `.html` type (lowercase).
