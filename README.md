# How To: Presentations with pandoc and `reveal.js`

- Download and install `pandoc` (see [here](https://pandoc.org/)))
- Create your slides in a markdown file
- Run to convert your markdown `slides.md` into a html file `slides.html`:

### MacOS

```shell
pandoc -t revealjs slides.md -o index.html  \
	--mathjax \
	--standalone \
	--css=styles.css \
	--css=https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css
```

### Windows

```shell
pandoc -t revealjs slides.md -o index.html  ^
	--mathjax ^
	--standalone ^
	--css=styles.css ^
	--css=https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css
```

In order to host the presentation online check out https://pages.github.com/