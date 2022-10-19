#  Amphitheatre Website

The website is hosted at https://amphitheatre.app. This repository houses all the assets required to build the Amphitheatre website. Built with [Zola](https://www.getzola.org/), written using
[CommonMark](https://commonmark.org/), a well-defined and highly compatible
[Markdown](https://www.markdownguide.org/) specification. Pull requests welcome!

[![Website](https://img.shields.io/website?up_message=online&url=https%3A%2F%2Famphitheatre.app)](https://amphitheatre.app)
[![Netlify](https://img.shields.io/netlify/0ced0b15-9c72-4816-9081-ff67524aad6b)](https://amphitheatre.app)
[![License](https://img.shields.io/github/license/amphitheatre-app/website)](https://github.com/amphitheatre-app/website/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/amphitheatre-app/website)](https://github.com/amphitheatre-app/website/graphs/contributors)
[![GitHub issues](https://img.shields.io/github/issues/amphitheatre-app/website)](https://github.com/amphitheatre-app/website/issues)

## Developing

``` bash
$ zola serve # dev server at http://127.0.0.1:1111
```

This will build and serve the site using a local server. Before starting, Zola
will delete the output directory (by default public in project root) to start
from a clean slate.

The serve command will watch all your content and provide live reload without a
hard refresh if possible. If you are using WSL2 on Windows, make sure to store
the website on the WSL file system.

Some changes cannot be handled automatically and thus live reload may not always
work. If you fail to see your change or get an error, try restarting zola serve.

## Deploying

The site is automatically deployed when commits land in `master`, via
[Netlify](https://www.netlify.com/).

If you are the maintainer of a community translation fork and would like to
deploy via Netlify instead of GitHub pages, please ping @wangeguo in an issue to
request a Netlify team membership and DNS update.

## Want to help with the translation?

If you feel okay with translating quite alone, you can fork the repo, post a
comment on the [Community Translation
Announcements](https://github.com/amphitheatre-app/website/issues/1) issue page to
inform others that you're doing the translation and go for it.