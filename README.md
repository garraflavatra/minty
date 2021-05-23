<h1 align="center">Minty</h1>
<p align="center">A fresh Bootstrap theme</p>
<p align="center"><strong>
  <a href="https://garraflavatra.github.io/minty/" rel="nofollow">Demo</a> - <a href="https://github.com/garraflavatra/minty/blob/master/README.md">Docs</a> - <a href="https://github.com/garraflavatra/minty">GitHub</a> - <a href="https://www.npmjs.com/package/minty-bootstrap">NPM</a>
</strong></p>
<p align="center">
  <a href="https://www.npmjs.com/package/minty-bootstrap"><img alt="npm" src="https://img.shields.io/npm/v/minty-bootstrap"></a>
  <img alt="GitHub commits since latest release (by date including pre-releases)" src="https://img.shields.io/github/commits-since/garraflavatra/minty/latest?include_prereleases">
  <img alt="npm" src="https://img.shields.io/npm/dt/minty-bootstrap?logo=npm">
  <img alt="GitHub issues" src="https://img.shields.io/github/issues/garraflavatra/minty">
</p>

> Screenshot:
> ![Screenshot of Minty](https://github.com/garraflavatra/minty/raw/master/docs/screenshot.png)

## Table of contents

- [Installation and usage](#installation-and-usage)
- [Contributing](#contributing)

## Installation and usage

Install Minty via `npm`:

```shell
npm install minty-bootstrap
```

Or, download it [here](https://github.com/garraflavatra/minty/releases/latest).

Add it to your project:

```html
<link rel="stylesheet" src="/your/path/to/minty.css">
```

Or, when you're using `npm`:

```html
<link rel="stylesheet" src="node_modules/minty-bootstrap/dist/minty.css">
```

You can use the minified version of Minty by replacing `minty.css` to `minty.min.css`.

Bootstrap's JavaScript isn't included, so you have to install the JS files separately:

```html
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
```

You don't have to install Bootstrap's CSS, everything's included in this CSS file.

For usage of Minty, just head over to [the Bootstrap docs](https://getbootstrap.com).

## Contributing

1. Clone this repository:
   ```bash
   git clone https://github.com/garraflavatra/minty.git
   ```
2. Install dev dependencies:
   ```bash
   npm install
   ```
3. Make changes to `src/*.scss`.
4. Run
   ```bash
   npm start
   ```
5. Add your changes:
   ```bash
   git add *
   ```
6. Commit your changes.
   ```bash
   git commit -m
   ```
7. Create a pull request.

Thanks for contributing!
