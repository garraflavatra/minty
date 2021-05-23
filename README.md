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
> ![Screenshot of Minty](https://github.com/garraflavatra/minty/raw/main/docs/screenshot.png)

## Versions

| Minty version | Bootstrap version | Docs                                                                |
|---------------|-------------------|---------------------------------------------------------------------|
| 2.x.x         | 5.x.x             | current                                                             |
| 1.x.x         | 4.x.x             | [here](https://github.com/garraflavatra/minty/blob/1.1.0/README.md) |

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
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>

<!-- or separate: -->

<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.min.js" integrity="sha384-Atwg2Pkwv9vp0ygtn1JAojH0nYbwNJLPhwyoVbhoPwBhjQPR5VtM2+xf0Uwh9KtT" crossorigin="anonymous"></script>
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
