# Introduction

![Card](~@github/card.svg)

::: tip PHPDoc-VuePress
Template for generating your PHP API documentation in a pretty VuePress format.
:::

![GitHub release](https://img.shields.io/github/tag/nelson6e65/phpdoc-vuepress.svg?logo=github)
![Latest Version](https://img.shields.io/packagist/v/nelson6e65/phpdoc-vuepress.svg)
![Latest unstable Version](https://img.shields.io/packagist/vpre/nelson6e65/phpdoc-vuepress.svg?label=unstable)
![License](https://img.shields.io/github/license/nelson6e65/phpdoc-vuepress.svg)
![Coding activity](https://wakatime.com/badge/github/nelson6e65/phpdoc-vuepress.svg)

This package provides a **phpDocumentor** template to generate the API documentation of your code to be integrated in a nice looking [VuePress](https://vuepress.vuejs.org) project.

> Only tested with the default theme of VuePress.

## Features

This template will generate six VuePress `*.md` files with the DocBlock documentation in your target directory:

- `README.md`: Entry point of your API Documentation. Contains, at the moment, an introduction and references to blocks used in the site.
- `classes.md`: Contains all classes, sorted by namespace.
- `interfaces.md`: Contains all interfaces, sorted by namespace.
- `traits.md`: Contains all traits, sorted by namespace.
- `constants.md`: Contains all global constants, sorted by namespace.
- `functions.md`: Contains all global functions, sorted by namespace.

## Demos

Check a demo of documentation generated with this template in [Demo](/demo/)

**Real projects using this template:**

- PHP: Nelson Martell Library - [https://php-nml.netlify.app/api](https://php-nml.netlify.app/api).

> Do you use this template? Add it here! 😀

## License

![License](https://img.shields.io/github/license/nelson6e65/phpdoc-vuepress.svg)

Copyright (c) 2018-2021 Nelson Martell

Read the [`LICENSE` file](https://github.com/nelson6e65/phpdoc-vuepress/blob/master/LICENSE) for details.

> **Note:** This template is based on Markdown template created by [@cvuorinen](https://github.com/cvuorinen): [cvuorinen/phpdoc-markdown-public](https://github.com/cvuorinen/phpdoc-markdown-public).
