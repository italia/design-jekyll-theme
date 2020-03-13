# Design Jekyll Theme

A Jekyll theme based on the [UI Kit](https://github.com/italia/design-ui-kit)
and built with [Bootstrap Italia](https://github.com/italia/bootstrap-italia/).

## Getting started

The theme itself is a starting point for a Jekyll-based website. You can refer
to the [official Jekyll docs](https://jekyllrb.com/docs/) for further details
on how to install it locally.

If you already have `bundler` installed, you can install jekyll and budler gems
with:

`bundle install`

However, if you want to install the dependencies locally you can run:

`bundle install --path vendor/bundle`

You can build the site and make it available on a local server with:

`bundle exec jekyll serve --config {_config.yml, _config_dev.yml}`

picking one of the two config files where:

*  _config.yml is the production file
*  _config_dev.yml is the development file.

### Notes

You can run the server just with `bundle exec jekyll serve`: the webiste will
be available on http://localhost:4000/design-jeyll-theme. This is the default
settings to allow usage with GitHub pages.

The aforementioned addition of `_config_dev.yml` is needed to run the server on
http://localhost:4000 without any subpath.

# License
This repository is licensed with a BSD-3-Clause license. Please check the
[LICENSE](LICENSE) file to know more details about this.
