# Akay

Akay is an Turkey word also a static site generator [PHP](https://www.php.net/).

The static site generators was inspired by [Jekyll](https://jekyllrb.com/), [Eleventy](https://www.11ty.dev/) and [Lume](https://lumeland.github.io/) but it's faster, simpler and easier to configure.

- Using a Front Matter, Markdown, HTML, Includes, Layouts, Assets and Datas.
- `config.yml` support like [Jekyll](https://jekyllrb.com/).

Coming Soon for packagist release.

## Getting Started

Make sure you have [Composer installed](https://getcomposer.org/doc/00-intro.md):

```
composer require --dev akayjun/akay
```

Create your example page using a Nunjucks file `index.html`.

```html
---
title: Welcome to my page
---
<html>
  <head>
    <title>{{ title }}</title>
  </head>
  <body>
    <h1>{{ title }}</h1>
  </body>
</html>
```

Build a page:

```
akay build
```

The HTML compile to save your `_site` directory.

## License

Licensed under the MIT License. See [LICENSE](LICENSE) for more information.
