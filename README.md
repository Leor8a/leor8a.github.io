# [Tequila Freak website]

[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/mmistakes/minimal-mistakes/master/LICENSE)
[![Jekyll](https://img.shields.io/badge/jekyll-%3E%3D%203.7-blue.svg)](https://jekyllrb.com/)
[![Ruby gem](https://img.shields.io/gem/v/minimal-mistakes-jekyll.svg)](https://rubygems.org/gems/minimal-mistakes-jekyll)
[![Tip Me via PayPal](https://img.shields.io/badge/PayPal-tip%20me-green.svg?logo=paypal)](https://www.paypal.me/mmistakes)
Yo hello, fellow programmer, you landed into 

www.tequilafreak.com 



Minimal Mistakes is a flexible two-column Jekyll theme, perfect for building personal sites, blogs, and portfolios. As the name implies, styling is purposely minimalistic to be enhanced and customized by you :smile:.

:sparkles: See what's new in the [CHANGELOG](CHANGELOG.md).

**If you enjoy this theme, please consider [supporting me](https://www.paypal.me/mmistakes) to continue developing and maintaining it.**

[![Support via PayPal](https://cdn.jsdelivr.net/gh/twolfson/paypal-github-button@1.0.0/dist/button.svg)](https://www.paypal.me/mmistakes)

**Note:** The theme uses the [jekyll-include-cache](https://github.com/benbalter/jekyll-include-cache) plugin which will need to be installed in your `Gemfile` and added to the `plugins` array of `_config.yml`. Otherwise you'll encounter `Unknown tag 'include_cached'` errors at build.

[![Minimal Mistakes live preview][2]][1]

[1]: https://mmistakes.github.io/minimal-mistakes/
[2]: screenshot.png (live preview)

![layout examples](screenshot-layouts.png)

## Notable features

- Bundled as a "theme gem" for easier installation/upgrading.
- Compatible with GitHub Pages.
- Support for Jekyll's built-in Sass/SCSS preprocessor.
- Nine different skins (color variations).
- Several responsive layout options (single, archive index, search, splash, and paginated home page).
- Optimized for search engines with support for [Twitter Cards](https://dev.twitter.com/cards/overview) and [Open Graph](http://ogp.me/) data.
- Optional [header images](https://mmistakes.github.io/minimal-mistakes/docs/layouts/#headers), [custom sidebars](https://mmistakes.github.io/minimal-mistakes/docs/layouts/#sidebars), [table of contents](https://mmistakes.github.io/minimal-mistakes/docs/helpers/#table-of-contents), [galleries](https://mmistakes.github.io/minimal-mistakes/docs/helpers/#gallery), related posts, [breadcrumb links](https://mmistakes.github.io/minimal-mistakes/docs/configuration/#breadcrumb-navigation-beta), [navigation lists](https://mmistakes.github.io/minimal-mistakes/docs/helpers/#navigation-list), and more.
- Commenting support (powered by [Disqus](https://disqus.com/), [Facebook](https://developers.facebook.com/docs/plugins/comments), Google+, [Discourse](https://www.discourse.org/), static-based via [Staticman](https://staticman.net/), and [utterances](https://utteranc.es/)).
- [Google Analytics](https://www.google.com/analytics/) support.
- UI localized text in English (default), Brazilian Portuguese (Português brasileiro), Catalan, Chinese, Danish, Dutch, French (Français), German (Deutsch), Greek, Hindi (हिंदी), Hungarian, Indonesian, Italian (Italiano), Japanese, Korean, Malayalam, Nepali (Nepalese), Persian (فارسی), Polish, Punjabi (ਪੰਜਾਬੀ), Romanian, Russian, Slovak, Spanish (Español), Swedish, Thai, Turkish (Türkçe), and Vietnamese.

## Skins (color variations)

This theme comes in nine different skins (in addition to the default one).

| `air` | `contrast` | `dark` |
| --- | --- | --- |
| [![air skin](https://mmistakes.github.io/minimal-mistakes/assets/images/air-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/air-skin-archive-large.png) | [![contrast skin](https://mmistakes.github.io/minimal-mistakes/assets/images/contrast-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/contrast-skin-archive-large.png) | [![dark skin](https://mmistakes.github.io/minimal-mistakes/assets/images/dark-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/dark-skin-archive-large.png) |

| `dirt` | `mint` | `sunrise` |
| --- | --- | --- |
| [![dirt skin](https://mmistakes.github.io/minimal-mistakes/assets/images/dirt-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/dirt-skin-archive-large.png) | [![mint skin](https://mmistakes.github.io/minimal-mistakes/assets/images/mint-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/mint-skin-archive-large.png) | [![sunrise skin](https://mmistakes.github.io/minimal-mistakes/assets/images/sunrise-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/sunrise-skin-archive-large.png) |

| `aqua` | `neon` | `plum` |
| --- | --- | --- |
| [![aqua skin](https://mmistakes.github.io/minimal-mistakes/assets/images/aqua-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/aqua-skin-archive-large.png) | [![neon skin](https://mmistakes.github.io/minimal-mistakes/assets/images/neon-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/neon-skin-archive-large.png) | [![plum skin](https://mmistakes.github.io/minimal-mistakes/assets/images/plum-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/plum-skin-archive-large.png) |

## Demo pages

| Name                                        | Description                                           |
| ------------------------------------------- | ----------------------------------------------------- |
| [Post with Header Image][header-image-post] | A post with a large header image. |
| [HTML Tags and Formatting Post][html-tags-post] | A variety of common markup showing how the theme styles them. |
| [Syntax Highlighting Post][syntax-post] | Post displaying highlighted code. |
| [Post with a Gallery][gallery-post] | A post showing several images wrapped in `<figure>` elements. |
| [Sample Collection Page][sample-collection] | Single page from a collection. |
| [Categories Archive][categories-archive] | Posts grouped by category. |
| [Tags Archive][tags-archive] | Posts grouped by tag. |

Additional sample posts are available under [posts archive][year-archive] on the demo site. Source files for these (and the entire demo site) can be found in [`/docs`](docs).

[header-image-post]: https://mmistakes.github.io/minimal-mistakes/layout-header-image-text-readability/
[gallery-post]: https://mmistakes.github.io/minimal-mistakes/post%20formats/post-gallery/
[html-tags-post]: https://mmistakes.github.io/minimal-mistakes/markup/markup-html-tags-and-formatting/
[syntax-post]: https://mmistakes.github.io/minimal-mistakes/markup-syntax-highlighting/
[sample-collection]: https://mmistakes.github.io/minimal-mistakes/recipes/chocolate-chip-cookies/
[categories-archive]: https://mmistakes.github.io/minimal-mistakes/categories/
[tags-archive]: https://mmistakes.github.io/minimal-mistakes/tags/
[year-archive]: https://mmistakes.github.io/minimal-mistakes/year-archive/


## Contributing

Having trouble working with the theme? Found a typo in the documentation? Interested in adding a feature or [fixing a bug](https://github.com/mmistakes/minimal-mistakes/issues)? Then by all means [submit an issue](https://github.com/mmistakes/minimal-mistakes/issues/new) or [pull request](https://help.github.com/articles/using-pull-requests/). If this is your first pull request, it may be helpful to read up on the [GitHub Flow](https://guides.github.com/introduction/flow/) first.

Minimal Mistakes has been designed as a base for you to customize and fit your site's unique needs. Please keep this in mind when requesting features and/or submitting pull requests. If it's not something that most people will use, I probably won't consider it. When in doubt ask. 

This goes for author sidebar links and "share button" additions -- I have no intention of merging in every possibly option, the essentials are there to get you started :smile:.

### Pull Requests

When submitting a pull request:

1. Clone the repo.
2. Create a branch off of `master` and give it a meaningful name (e.g. `my-awesome-new-feature`).
3. Open a pull request on GitHub and describe the feature or fix.

Theme documentation and demo pages can be found in the [`/docs`](docs) if submitting improvements, typo corrections, etc.

## Development

To set up your environment to develop this theme, run `bundle install`.

To test the theme, run `bundle exec rake preview` and open your browser at `http://localhost:4000/test/`. This starts a Jekyll server using content in the `test/` directory. As modifications are made to the theme and test site, it will regenerate and you should see the changes in the browser after a refresh.

---


### Other:

- [Jekyll](http://jekyllrb.com/)
- [jQuery](http://jquery.com/)
- [Susy](http://susy.oddbird.net/)
- [Breakpoint](http://breakpoint-sass.com/)
- [Magnific Popup](http://dimsemenov.com/plugins/magnific-popup/)
- [FitVids.JS](http://fitvidsjs.com/)
- [GreedyNav.js](https://github.com/lukejacksonn/GreedyNav)
- [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
- [Gumshoe](https://github.com/cferdinandi/gumshoe)
- [jQuery throttle / debounce](http://benalman.com/projects/jquery-throttle-debounce-plugin/)
- [Lunr](http://lunrjs.com)

---

## License

The MIT License (MIT)

Copyright (c) 2020-2020 Luis Ochoa and contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
