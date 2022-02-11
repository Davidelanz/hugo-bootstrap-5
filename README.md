# Hugo Bootstrap v5 Theme

This is a simple Hugo [Bootstrap v5](https://getbootstrap.com/) theme, inspired by [hugo-bootstrap](https://github.com/AuthorGithub/hugo-bootstrap) and [hugo-bootstrap-5](https://github.com/NotWoods/hugo-bootstrap-5).

## Installation

From the root of your Hugo site, you can install the theme by typing the following command:

```shell
git submodule add https://github.com/Davidelanz/hugo-bootstrap-5.git themes/hugo-bootstrap-5
git submodule init
git submodule update
```

Then, to update the theme to the latest version:

```
$ git submodule update --remote themes/hugo-bootstrap-5
```

## Demo

You can find a demo STILL NOWHERE.

## Screenshots

![preview](https://raw.githubusercontent.com/Davidelanz/hugo-bootstrap-5/master/images/screenshot.png)
![preview](https://raw.githubusercontent.com/Davidelanz/hugo-bootstrap-5/master/images/screenshot2.png)

## Configuration

Check `example_site/config.toml` for an example configuration.

## Brand

The brand can be overriden by adding your own layout `layouts/partials/brand.html`. Check `example_site/layouts/partials/brand.html` for an example.

## Menu

The navbar displays the `main` menus by default. You can find more details about how to configure it [here](https://gohugo.io/templates/menu-templates/), as well as in the `example_site`.

## Multilanguage

The theme supports multiple languages.

You can find the default translation bundles in `i18n` (english and spanish by default).

## License

Open sourced under the [MIT license](./LICENSE.md).
