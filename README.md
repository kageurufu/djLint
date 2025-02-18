
<h1 align="center">
  <br>
  <a href="https://www.djlint.com"><img src="https://raw.githubusercontent.com/Riverside-Healthcare/djLint/master/docs/src/static/img/icon.png" alt="djLint Logo" width="270"></a>
  <br>
</h1>
 
<h4 align="center">The missing formatter and linter for HTML templates.</h4>

<p align="center">
   <a href="https://codecov.io/gh/Riverside-Healthcare/djlint">
     <img src="https://codecov.io/gh/Riverside-Healthcare/djlint/branch/master/graph/badge.svg?token=eNTG721BAA" alt="Codecov Status">
   </a>
   <a href="https://github.com/Riverside-Healthcare/djlint/actions/workflows/test.yml">
     <img src="https://github.com/Riverside-Healthcare/djlint/actions/workflows/test.yml/badge.svg" alt="Test Status">
   </a>
   <a href="https://www.codacy.com/gh/Riverside-Healthcare/djlint/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Riverside-Healthcare/djlint&amp;utm_campaign=Badge_Grade">
     <img src="https://app.codacy.com/project/badge/Grade/dba6338b0e7a4de896b45b382574f369" alt="Codacy Status">
   </a>
   <a href="https://pepy.tech/project/djlint">
     <img src="https://pepy.tech/badge/djlint" alt="Downloads">
   </a>
   <a href="https://discord.gg/taghAqebzU">
     <img src="https://img.shields.io/badge/chat-discord-green" alt="Discord Chat">
   </a>
   <a href="https://pypi.org/project/djlint/">
     <img src="https://img.shields.io/pypi/v/djlint" alt="Pypi Download">
   </a>
</p>

<h4 align="center"><a href="https://www.djlint.com">How to use</a> • <a href="https://www.djlint.com/ru/">Как пользоваться</a> • <a href="https://www.djlint.com/fr/">Utilisation</a></h4>
<h4 align="center">What lang are you using?</h4>

<p align="center">
   <a href="https://djlint.com/docs/languages/django/">Django</a> • <a href="https://djlint.com/docs/languages/jinja/">Jinja</a> • <a href="https://djlint.com/docs/languages/nunjucks/">Nunjucks</a> • <a href="https://djlint.com/docs/languages/twig/">Twig</a> • <a href="https://djlint.com/docs/languages/handlebars/">Handlebars</a> • <a href="https://djlint.com/docs/languages/mustach/">Mustache</a> • <a href="https://djlint.com/docs/languages/golang/">GoLang</a> • <a href="https://djlint.com/docs/languages/angular/">Angular</a>
</p>

<p align="center">
  <img src="https://github.com/Riverside-Healthcare/djLint/blob/aa9097660d4a2e840450de5456f656c42bc7dd34/docs/src/static/img/demo-min.gif" alt="demo" width="600">
</p>

## 🤔 For What?

Once upon a time all the other programming languages had a formatter and linter. Css, javascript, python, the c suite, typescript, ruby, php, go, swift, and you know the others. The cool kids on the block.

HTML templates were left out there on their own, in the cold, unformatted and unlinted :( The dirty corner in your repository. Something had to change.

**djLint is a community build project to and add consistency to html templates.**

## ✨ How?

Grab it with `pip`

```bash
pip install djlint
```

Lint your project

```bash
djlint . --extension=html.j2 --lint
```
Check your format

```bash
djlint . --extension=html.j2 --check
```
Fix my format!
```bash
djlint . --extension=html.j2 --reformat
```

## 💙 Like it?

Add a badge to your projects ```readme.md```:

```md
[![Code style: djlint](https://img.shields.io/badge/html%20style-djlint-blue.svg)](https://www.djlint.com)
```

Add a badge to your ```readme.rst```:

```rst
.. image:: https://img.shields.io/badge/html%20style-djlint-blue.svg
   :target: https://www.djlint.com
```
Looks like this:

[![djLint](https://img.shields.io/badge/html%20style-djLint-blue.svg)](https://github.com/Riverside-Healthcare/djlint)


## 🛠️ Can I help?

Yes! 

*Would you like to add a rule to the linter?* Take a look at the [linter docs](https://djlint.com/docs/linter/) and [source code](https://github.com/Riverside-Healthcare/djLint/blob/master/src/djlint/rules.yaml)

*Are you a regex pro?* Benchmark and submit a pr with improved regex for the [linter rules](https://github.com/Riverside-Healthcare/djLint/blob/master/src/djlint/rules.yaml)

**⚠️ Help Needed! ⚠️** *Good with python?* djLint was an experimental project and is catching on with other devs. Help out with a rewrite of the formatter to improve speed and html style for edge cases. Contribute on the [2.0 branch](https://github.com/Riverside-Healthcare/djLint/tree/block_indent)

## 🏃 Other Tools Of Note

* [DjHTML](https://github.com/rtts/djhtml) A pure-Python Django/Jinja template indenter without dependencies.
* [HTMLHint](https://htmlhint.com) Static code analysis tool you need for your HTML
* [curlylint](https://www.curlylint.org) Experimental HTML templates linting for Jinja, Nunjucks, Django templates, Twig, Liquid
