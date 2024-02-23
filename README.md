# 🧪 Zola Sanbox

<p align="">
  <img src="https://img.shields.io/github/languages/code-size/semanticdata/zola-sandbox" />
  <img src="https://img.shields.io/github/repo-size/semanticdata/zola-sandbox" />
  <img src="https://img.shields.io/github/commit-activity/t/semanticdata/zola-sandbox" />
  <img src="https://img.shields.io/github/last-commit/semanticdata/zola-sandbox" />
  <img src="https://img.shields.io/website/https/semanticdata.github.io/zola-sandbox.svg" />
</p>

This repository is used to test new web elements. It is an amalgamation of code snippets, all weaved together by Zola.

## Table of Contents

<details>
<summary>Show/Hide</summary>

- [Overview](#overview)
- [Table of Contents](#table-of-contents)
- [Running the Site Locally](#running-the-site-locally)
  - [Requirements](#requirements)
  - [Quick Start](#quick-start)
  - [Useful Commands](#useful-commands)
- [Customization](#customization)
  - [Custom CSS Styles](#custom-css-styles)
- [Reporting Issues](#reporting-issues)
- [Contributing](#contributing)
- [Acknowledgements and Attributions](#acknowledgements-and-attributions)
- [License](#license)

</details>

## Running the Site Locally

Tips that will help you develop and preview the site locally.

### Requirements

Before using the theme, you need to install [Zola](https://www.getzola.org/documentation/getting-started/installation/) ≥ 0.18.0.

### Quick Start

```bash
# clone the repo
git clone git@github.com:semanticdata/zola-sandbox.git
# change directory into the cloned folder
cd zola-sandbox
# serve the site locally
zola serve
# open http://127.0.0.1:1111/ in the browser
```

For more detailed instructions, visit the [Documentation](https://www.getzola.org/documentation/themes/installing-and-using-themes/) page about installing and using themes.

### Useful Commands

A short list of commands that will help you develop your own version of the theme.

| Command                    | Description                |
| -------------------------- | -------------------------- |
| `zola init <my-repo>`      | Initiate new Zola site     |
| `zola build`               | Build only                 |
| `zola serve`               | Build and Serve            |

## Customization

You can changed the configuration, templates and content yourself. Refer to the `config.toml`, and templates files for ideas. In most cases you only need to modify the contents of `config.toml` to customize the appearance of your blog. Make sure to visit tyhe [Zola Documentation](https://www.getzola.org/documentation/getting-started/overview/).

### Custom CSS Styles

Adding custom CSS is as easy as adding your styles to `sass/_custom.scss`. This is made possible because SCSS files are backwards compatible with CSS. This means you can type normal CSS code into a SCSS file and it will be valid.

## Acknowledgements and Attributions

The icons used throughout the site are kindly provided by [UXWing](https://uxwing.com/license/). Read their [license](https://uxwing.com/license/).

Other icons used come from [Remix Icon](https://remixicon.com/). Check out their [license](https://remixicon.com/license).

## License

Source code in this repository is available under the [MIT](LICENSE) license. You are free to use this code however you like. That said, some acknowledgement would be well received.
