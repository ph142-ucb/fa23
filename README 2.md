# su21
Course website for Public Health 142: Introduction to Probability and Statistics in Biology and Public Health. This website uses 'Just the Class,' a Jekyll template for course websites developed by Kevin Lin.

# PH 142

This repo hosts the source files for PH142's Summer 2021 [website](https://ph142-ucb.github.io/su21/).

This site is built from Kevin Lin's [Just the Class](https://github.com/kevinlin1/just-the-class).

### Editing the website

1. Clone this repo.
```bash
$ git clone https://github.com/ph142-ucb/su21.git
```
2. (**If already cloned**) pull any changes that might have been made in order to avoid merge conflicts at a later point:
```bash
$ git pull
```
3. To make edits, checkout to a separate branch and make the necessary changes:
```bash
$ git checkout -b '<name of branch>'
```
4. Add and commit changes to your branch, then push them to the remote su21 repository on Github:
```bash
$ git add -A
$ git commit -m "<commit message>"
$ git push
```
5. Create a pull request on the (su21 Github page)[https://github.com/ph142-ucb/su21/pulls] to get it approved by either Chandler or Mi-suk.

See this [amazing video guide](https://www.youtube.com/watch?v=azPPK5aOcV0&feature=youtu.be&t=460s) that [Suraj](https://github.com/surajrampure) made for Data100.

### Local development environment

Just the Class is built for [Jekyll](https://jekyllrb.com), a static site generator. View the [quick start guide](https://jekyllrb.com/docs/) for more information. Just the Docs requires no special Jekyll plugins and can run on GitHub Pages' standard Jekyll compiler.

1. Follow the GitHub documentation for [Setting up your GitHub Pages site locally with Jekyll](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll).
2. Start your local Jekyll server.
```bash
$ bundle exec jekyll serve
```
3. Point your web browser to [http://localhost:4000](http://localhost:4000)
4. Reload your web browser after making a change to preview its effect.

For more information, refer to [Just the Docs](https://pmarsceill.github.io/just-the-docs/).
