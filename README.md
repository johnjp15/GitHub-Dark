<p align="center">
  <img alt="githubdark-logo" src="https://rawgit.com/StylishThemes/logos/master/github.dark/githubdark-mini.svg" width="580">
  <br>
  <a href="https://github.com/StylishThemes/GitHub-Dark/tags">
    <img src="https://img.shields.io/github/tag/StylishThemes/GitHub-Dark.svg?label=%20tag%20" alt="Tag">
  </a>
  <a href="https://github.com/StylishThemes/GitHub-Dark/stargazers">
    <img src="http://github-svg-buttons.herokuapp.com/star.svg?user=StylishThemes&repo=GitHub-Dark&style=flat&background=007ec6" alt="Star">
  </a>
  <a href="http://github.com/StylishThemes/GitHub-Dark/fork">
    <img src="http://github-svg-buttons.herokuapp.com/fork.svg?user=StylishThemes&repo=GitHub-Dark&style=flat&background=007ec6" alt="Fork">
  </a>
  <a href="https://david-dm.org/StylishThemes/GitHub-Dark?type=dev">
    <img src="https://img.shields.io/david/dev/StylishThemes/GitHub-Dark.svg?label=%20devDependencies%20" alt="devDependencies">
  </a>
  <a href="https://gitter.im/StylishThemes/GitHub-Dark">
    <img src="https://img.shields.io/gitter/room/StylishThemes/Github-Dark.js.svg?maxAge=2592000" alt="Gitter">
  </a>
</p>
<h2 align="center">Your eyes will :heart: you.</h2>

## Preview
![](./images/screenshots/after_blue.png)

## Installing

* If using Stylish:
  * Get the Stylish addon for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/2108/), [Chrome](https://chrome.google.com/extensions/detail/fjnbnpbmkenffdnngjfgmeleoegfcffe), [Opera](https://addons.opera.com/en/extensions/details/stylish/), [Safari](http://sobolev.us/stylish/) and [Firefox Mobile](https://addons.mozilla.org/en-US/firefox/addon/2108/).
  * Then install this style using:
    * [userstyles.org](http://userstyles.org/styles/37035) (with customization options)
    * or, add it [manually](https://raw.githubusercontent.com/StylishThemes/GitHub-Dark/master/github-dark.css) into the editor.
      * Use the [grunt build process](https://github.com/StylishThemes/GitHub-Dark/wiki/Build) to customize your GitHub Dark theme.
      * Please refer to the [installation documentation](https://github.com/StylishThemes/GitHub-Dark/wiki/Install) for more details.
* Or, use our [GitHub-Dark Script](https://github.com/StylishThemes/GitHub-Dark-Script) which requires a [user script addon](https://github.com/StylishThemes/GitHub-Dark-Script/wiki/Install), but allows dynamic style changes & updates:bangbang:

## Updating

If a recent change by GitHub broke the style, chances are that we already fixed it. Make sure to reinstall from [userstyles.org](https://userstyles.org/styles/37035/github-dark) or [GitHub](https://raw.githubusercontent.com/StylishThemes/GitHub-Dark/master/github-dark.css) before opening an issue. Note that only Stylish for Firefox performs automatic style updates.

## Additional GitHub Customization

* [GitHub-code-wrap](https://github.com/StylishThemes/GitHub-code-wrap) to wrap long lines in code boxes
* [GitHub-FixedHeader](https://github.com/StylishThemes/GitHub-FixedHeader) to have a fixed header
* [GitHub-Commit-Limit](https://github.com/StylishThemes/GitHub-Commit-Limit) to show line length limits when editing a commit message
* [GitHub-Selected-Tab-Color](https://github.com/StylishThemes/GitHub-Selected-Tab-Color)

## Supported GitHub Addons

* [ZenHub](https://www.zenhub.io/)
* [Octotree](https://github.com/buunguyen/octotree/#octotree)
* [GitHub Awesome Autocomplete](https://github.com/algolia/github-awesome-autocomplete)
* [GitHub canned responses](https://github.com/notwaldorf/github-canned-responses#how-to-get-it)
* [Lovely forks](https://github.com/musically-ut/lovely-forks#lovely-forks)

## Available Syntax Highlighting Themes ([Demo](https://stylishthemes.github.io/GitHub-Dark/))

| Theme                      | GitHub | CodeMirror | Jupyter  |
|----------------------------|:------:|:----------:|:--------:|
| Ambiance                   |   *    |     *      |          |
| Chaos                      |   *    |            |          |
| Clouds Midnight            |   *    |            |          |
| Cobalt                     |   *    |     *      |          |
| GitHub Dark                |   *    |            |     *    |
| Idle Fingers               |   *    |            |     *    |
| Kr Theme                   |   *    |            |          |
| Merbivore                  |   *    |            |          |
| Merbivore Soft             |   *    |            |          |
| Mono Industrial            |   *    |            |          |
| Mono Industrial Clear      |   *    |            |          |
| Monokai                    |   *    |     *      |     *    |
| Monokai Spacegray Eighties |   *    |     *      |     *    |
| Obsidian                   |   *    |            |     *    |
| Pastel on Dark             |   *    |     *      |     *    |
| Solarized Dark             |   *    |     *      |     *    |
| Terminal                   |   *    |            |          |
| Tomorrow Night             |   *    |            |          |
| Tomorrow Night Blue        |   *    |            |     *    |
| Tomorrow Night Bright      |   *    |     *      |     *    |
| Tomorrow Night Eigthies    |   *    |     *      |     *    |
| Twilight                   |   *    |     *      |     *    |
| Vibrant Ink                |   *    |     *      |          |

* Partial support for [Codemirror](https://codemirror.net/demo/theme.html) and [Jupyter notebook syntax highlighting](https://github.com/sujitpal/statlearning-notebooks/blob/master/src/chapter2.ipynb) themes.
* If the selected theme does not have an associated CodeMirror or Jupyter theme, it will fall back to a Twilight theme.
* Please provide a pull request if you have or want to create a missing theme.

## Notes

* If you're using a custom domain for GitHub Enterprise, be sure to include it though a `@-moz-document` rule (Firefox) or add it to the `Applies to` section in (Chrome).
* If you want GitHub commit messages to use a monospaced font, and have a background color indicating the width limits, check out [GitHub Commit Limit](https://github.com/StylishThemes/GitHub-Commit-Limit).

## Contributions

If you would like to contribute to this repository, please...

1. Fork
2. Make changes (please read the [contribution guidelines](./.github/CONTRIBUTING.md) and abide by them)
3. Create a pull request!

Thanks to all that have [contributed](./AUTHORS) so far!

## Recent Changes

See the [full change log](https://github.com/StylishThemes/GitHub-Dark/wiki).

### Version 1.16.3 (10/8/2016)

* Review:
  * Colored review item icons
  * Fix pending review boxes
* Organization:
  * Fixes for the invite page
* Status:
  * Various text color fixes

### Version 1.16.2 (10/1/2016)

* Themes:
  * Update `github/_template.css`.
  * Add GitHub Dark theme (GitHub &amp; Jupyter).

### Version 1.16.1 (10/1/2016)

* Form Select: Fix arrow icon.
* Developer:
  * Fix plain code style. See [issue #424](https://github.com/StylishThemes/GitHub-Dark/issues/424).
  * Transparent table background & add border to `pre`.
* Themes:
  * Add partial Dracula support for CodeMirror &amp; Jupyter. See [issue #415](https://github.com/StylishThemes/GitHub-Dark/issues/415).
  * Fix up Dracula CodeMirror theme.
  * Added Monokai - Spacegray Eighties theme from [Sublime](https://github.com/pyoio/monokai-spacegray)  [pull #426](https://github.com/StylishThemes/GitHub-Dark/pull/426); thanks [@torrentails](https://github.com/torrentails); closes [issue #425](https://github.com/StylishThemes/GitHub-Dark/issues/425).
* Meta:
  * Ignore build folder in case it is not removed. See [issue #422](https://github.com/StylishThemes/GitHub-Dark/issues/422).
  * Remove `.min.css` files from git. Fixes [issue #424](https://github.com/StylishThemes/GitHub-Dark/issues/424).
  * Revert "Meta: Remove `.min.css` files from git". Fixes [issue #424](https://github.com/StylishThemes/GitHub-Dark/issues/424).
  * Move `archive` folder to https://github.com/StylishThemes/Syntax-Themes.
* Demo
  * Use source theme files. See [issue #424](https://github.com/StylishThemes/GitHub-Dark/issues/424).
  * Add Monokai Spacegray Eighties min &amp; demo.

### Version 1.16.0 (9/25/2016)

* Global: Remove `ace_` and `CodeMirror` selectors from the main theme. See [issue #422](https://github.com/StylishThemes/GitHub-Dark/issues/422).
* Guides: Brighten headers. Fixes [issue #418](https://github.com/StylishThemes/GitHub-Dark/issues/418).
* Trending: Style subheading.
* Organization: Add border to team info box. Fixes [issue #420](https://github.com/StylishThemes/GitHub-Dark/issues/420).
* Explore: Brighten subtitle.
* Themes:
  * Switch Twilight from ACE to CodeMirror. See [issue #422](https://github.com/StylishThemes/GitHub-Dark/issues/422).
  * Add CodeMirror theme for Ambiance.
  * Add CodeMirror theme for Cobalt.
  * Add CodeMirror theme for Monokai.
  * Add CodeMirror theme for Pastel-on-Dark.
  * Add CodeMirror theme for Solarized-Dark.
  * Add CodeMirror theme for Tomorrow-Night-Bright.
  * Add CodeMirror theme for Tomoorow-Night-Eighties.
  * Add CodeMirror theme for Vibrant Ink.
  * Restructure folders.
* Editor: Fix selection and remove selection style out of theme. See [issue #422](https://github.com/StylishThemes/GitHub-Dark/issues/422).
* Meta:
  * Add "Updating" section to README.
  * Update devDependencies.
  * Update issue template with instructions.
  * Switch theme src and min location.
  * Build min css from separate files with Twilight fallback. See [issue #422](https://github.com/StylishThemes/GitHub-Dark/issues/422).

### Version 1.15.4 (9/21/2016)

* Developer: More tweaks.
* Meta:
  * Optimize default background image further.
  * Optimize PNGs, add select-arrow image.
