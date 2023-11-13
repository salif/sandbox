**⚠ This repo is not being developed. It only serves as web design/deployment sandbox. ⚠**

<h1 align=center>Zola Testing Repo</h1>

<p align="center">
  <img src="https://img.shields.io/github/languages/code-size/semanticdata/zola-testing" />
  <img src="https://img.shields.io/github/repo-size/semanticdata/zola-testing" />
  <img src="https://img.shields.io/github/commit-activity/t/semanticdata/zola-testing" />
  <img src="https://img.shields.io/github/last-commit/semanticdata/zola-testing" />
  <img src="https://img.shields.io/website/https/miguelpimentel.do/zola-testing.svg" />
</p>

This repo is used to test new web elements. It is an amalgamation of code snippets, all weaved together by Zola.

## Requirements

Before using the theme, you need to install the [Zola](https://www.getzola.org/documentation/getting-started/installation/) ≥ 0.17.2.

## Quick Start

```bash
git clone git@github.com:semanticdata/zola-minimalistic.git
cd zola-minimalistic
zola serve
# open http://127.0.0.1:1111/ in the browser
```

## Customization

You can customize your configurations, templates and content for yourself. Look
at the `config.toml`, `theme.toml` and templates files in this repo for an idea.

In most cases you only need to modify the content in the `config.toml` file to
custom your blog, including different expressions in your speaking language.

### Custom CSS styles

Adding your custom css is as easy as adding your own styles to the `sass/_custom.scss` file.

## Useful Commands

| Command                    | Description                |
| -------------------------- | -------------------------- |
| `zola build`               | Build only                 |
| `zola serve`               | Build and Serve            |

## License

Source code in this repository is available under the [MIT](LICENSE) license. You are free to use this code however you see fit. That said, some acknowledgement would be well received.
