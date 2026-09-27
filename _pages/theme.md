# Academic Pages

Welcome to the Academic Pages GitHub Pages repository for Jekyll. You can find documentation for the theme at the [Academic Pages Wiki](https://github.com/academicpages/academicpages.github.io/wiki).

To use the theme, you can either **[create your own repository](#create-your-repository)** or **[clone this repository](#clone-this-repository)**.

---

This repository is powered by **[GitHub Pages](https://pages.github.com)**, where sites are hosted directly from a repository, with no need to worry about updating a web server or data feed. Using a combination of structured data and Liquid templates (a template language used by Jekyll), you can create rich, dynamic content for your website without having to manually create pages with embedded content.

The most common way to contribute to the site is to add new content in markdown format by editing the templates for each of the different post formats (e.g. talks, papers, blog posts, etc.). You can read more in the [Contributing guide](https://github.com/academicpages/academicpages.github.io/wiki/Contributing-Guide).

This project is licensed under the terms of the MIT license. See the [LICENSE file](https://github.com/academicpages/academicpages.github.io/blob/master/LICENSE) for details.

## Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Create your repository](#create-your-repository)
- [Clone this repository](#clone-this-repository)
- [Citation](#citation)
- [Translations](#translations)
- [Contributors](#contributors)
- [License](#license)
- [Social Profiles](#social-profiles)
- [Funding](#funding)
- [Backers](#backers)

---

## Features

- **Based on Jekyll** - a static site generator that runs on GitHub Pages, no databases or server-side scripts needed, and it's **free**.
- **Responsive design** - the website works on mobile, tablet, and desktop.
- **No server-side scripting** - the website doesn't use PHP or JavaScript, so it loads quickly and is secure.
- **Separation of content and presentation** - content is stored in plain text files, with no dependence on a database. You can update your content without changing the design.
- **Simple content editor** - Markdown format is easy to learn and write. You can also use other tools (e.g. Google Docs, Microsoft Word) to edit your content and then copy it into Markdown.
- **Dynamically generated lists** - lists of recent posts, blog categories, tags, authors, etc., are generated automatically from structured data.
- **BibTeX bibliography** - works with BibTeX files to generate your publication list, saving time and avoiding errors with manual formatting.
- **TalkMap integration** - the template includes support for generating a map (displayed with `leaflet.js`) of every location you've given a talk, saved as talk metadata.
- **Math equations** - works with [MathJax](https://www.mathjax.org) for LaTeX equations.
- **Mermaid diagrams** - works with [Mermaid](https://mermaid.js.org/) to support diagramming.
- **Plotly charts** - works with [Plotly](https://plotly.com/javascript/) to support plotting.
- **Google Analytics** - you can add your Google Analytics tracking code and it will be included automatically in all pages.
- **Integrated with GitHub Pages** - free hosting on GitHub Pages with custom domain support (for GitHub user or organization pages, see [GitHub Pages Help](https://pages.github.com/)).
- **[MIT license](https://github.com/academicpages/academicpages.github.io/blob/master/LICENSE)** - the template is open source and free to use for commercial and non-commercial purposes.

---

## Getting Started

Use the **[theme creation template](https://github.com/academicpages/academicpages.github.io/generate)** to create your own site with this template. Once you've created your site, you can deploy it using **[GitHub Actions](#github-actions)** or **[deploy to GitHub Pages](#deploy-to-github-pages)**.

If you'd like to contribute to the development of the theme, you can **[clone this repository](#clone-this-repository)** and make your changes locally.

---

### **Create your repository**

1. Click the **[theme creation template](https://github.com/academicpages/academicpages.github.io/generate)** button in the top right of this README to generate a new repository with the same directory structure and files as the template, naming your repository `<username>.github.io`.
1. **(Optional)** Use the `Remote Repository Plugin` in [Jekyll Plus](https://github.com/thoughtbot/jekyll-remote-theme) if you want to use the remote theme without local modifications.
1. **(Optional)** If you want to customize the theme, see **[Caching](#caching)**.
1. **(Optional)** Run `jekyll serve` to preview the site locally. If you don't have Ruby installed, you can [install Ruby](https://www.ruby-lang.org/en/documentation/installation/) and install Jekyll.
1. **(Optional)** Run `jekyll build` to build the site.
1. **(Optional)** Run `bundle install` to install dependencies.

---

### **Clone this repository**

```bash
# Clone this repository
$ git clone https://github.com/academicpages/academicpages.github.io.git

# Go into the repository
$ cd academicpages.github.io

# Install dependencies
$ bundle install

# Run Jekyll
$ bundle exec jekyll serve
```

---

### **GitHub Actions**

The theme includes a GitHub Actions workflow that will build your site and push the output to the `gh-pages` branch. The workflow is defined in `.github/workflows/deploy.yml`. To use it, you'll need to:

1. **Fork the repository** on GitHub
1. **Change the domain name** in `_config.yml` in the `baseurl` variable.
1. **Change the title**, `email`, and other details in `_config.yml`.
1. **Run the workflow** (Actions tab) and wait for the build to finish.
1. **Change the settings** of the repository to use the `gh-pages` branch.

---

### **Jekyll Plugins**

The theme includes several Jekyll plugins:

- `jekyll-archives`
- `jekyll-sitemap`
- `jekyll-feed`
- `jekyll-seo-tag`
- `jemoji`

---

### **Jekyll 4.x compatibility**

The theme works with both Jekyll 3.x and 4.x. If you're using Jekyll 4.x, you'll need to:

1. **Update the gems** in `Gemfile` to use Jekyll 4.x.
2. **Remove `jekyll` from `Gemfile.lock`** and run `bundle install` again.
3. **Remove `gem "jekyll"` from `Gemfile`** and add `gem "github-pages"` to use GitHub Pages plugins.

---

### **GitHub Pages**

To deploy your site to GitHub Pages, you'll need to:

1. **Fork the repository** on GitHub.
1. **Change the domain name** in `_config.yml` in the `baseurl` variable.
1. **Run the workflow** (Actions tab) and wait for the build to finish.
1. **Change the settings** of the repository to use the `gh-pages` branch.

---

### **Tip: Update the theme**

The theme is regularly updated with new features and bug fixes. You can update your site by:

1. **Fork the repository** on GitHub.
2. **Create a new branch** for the update.
3. **Merge the new changes** from the theme repository into your branch.
4. **Push the changes** to your GitHub Pages.

---

### **Translations**

The theme is available in several languages. To change the language, edit the `lang` variable in `_config.yml` (e.g. `lang: zh-CN` for Simplified Chinese, `lang: zh-TW` for Traditional Chinese). If you'd like to contribute a translation, please open a pull request.

---

### **Contributors**

The list of contributors (in alphabetical order by first name):

- [Academic Pages](https://github.com/academicpages)
- [Anthony Oliver](https://github.com/aoliverg)
- [Benny Lin](https://github.com/bennylin)
- [Clement Pitot](https://github.com/clem21)
- [Danqi Chen](https://github.com/danqi)
- [Gregor Aisch](https://github.com/datanewbie)
- [Jeffrey Winters](https://github.com/jeffreycw)
- [Jens K. Ahrens](https://github.com/jenska)
- [Joel Ryan](https://github.com/jayroh)
- [Junxian He](https://github.com/junxianhe)
- [Kalle Westerdahl](https://github.com/kallewesterdahl)
- [Kristian Skagen](https://github.com/ksagen)
- [Lukas Rothert](https://github.com/lrothert)
- [Mani Ahmed](https://github.com/maniamh)
- [Manoj Vijay](https://github.com/manojvijay)
- [Marcus Williamson](https://github.com/marcuswilliamson)
- [Matt Kolker](https://github.com/mattkolker)
- [Nathan Clark](https://github.com/nathanclark)
- [Peter Sobot](https://github.com/petermolot)
- [Prasanna Swaminathan](https://github.com/pswami)
- [Robert Zupko](https://github.com/rjzupkoii)
- [Robert Reckless](https://github.com/robreck)
- [RossKieran](https://github.com/rosskieran)
- [Ryan McKernan](https://github.com/rmckernan)
- [Seongmin Lee](https://github.com/leeseongmin)
- [Sudeep Agarwal](https://github.com/upsuper)
- [Vijay Naicker](https://github.com/vijaynaicker)
- [W2](https://github.com/w2org)
- [William Ochoa](https://github.com/william-ochoa)
- [Yael Bahmani](https://github.com/yaelbahmani)

See [CONTRIBUTING.md](https://github.com/academicpages/academicpages.github.io/blob/master/CONTRIBUTING.md) for more details.

---

### **License**

This project is licensed under the terms of the MIT license. See the [LICENSE file](https://github.com/academicpages/academicpages.github.io/blob/master/LICENSE) for details.

---

### **Citation**

If you use the Academic Pages theme for your own website, please cite the template as follows:

```bibtex
@misc{academicpages2020,
  title = {Academic Pages},
  author = {{Academic Pages}},
  howpublished = {\url{https://academicpages.github.io}},
  year = {2020}
}
```

---

### **Social Profiles**

The theme uses the following social profile icons:

- [Blog](https://github.com/academicpages/academicpages.github.io/wiki/Blog)
- [DBLP](https://github.com/academicpages/academicpages.github.io/wiki/DBLP)
- [GitHub](https://github.com/academicpages/academicpages.github.io/wiki/GitHub)
- [Google Scholar](https://github.com/academicpages/academicpages.github.io/wiki/Google-Scholar)
- [LinkedIn](https://github.com/academicpages/academicpages.github.io/wiki/LinkedIn)
- [ORCID](https://github.com/academicpages/academicpages.github.io/wiki/ORCID)
- [ResearchGate](https://github.com/academicpages/academicpages.github.io/wiki/ResearchGate)
- [Twitter](https://github.com/academicpages/academicpages.github.io/wiki/Twitter)

---

### **Backers**

If you've benefitted from using the theme, please consider [supporting the project](https://github.com/sponsors/academicpages) to help us maintain and improve the template.

---

### **Funding**

If your research is funded by a grant, consider [adding your funding information](https://github.com/academicpages/academicpages.github.io/wiki/Funding) to your website.

---

### **License**

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

### **Artwork License**

The artwork (logo, icons, illustrations, etc.) is licensed under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

---

### **Social Media Icons**

The following icons are provided by [Social Icons](https://github.com/AcademiaInk/jekyll-theme-academia-icons):

- [Academic](https://github.com/AcademiaInk/jekyll-theme-academia-icons#academic)
- [LinkedIn](https://github.com/AcademiaInk/jekyll-theme-academia-icons#linkedin)
- [ResearchGate](https://github.com/AcademiaInk/jekyll-theme-academia-icons#researchgate)
- [Twitter](https://github.com/AcademiaInk/jekyll-theme-academia-icons#twitter)

---

### **Social Profiles (Included)**

The following social profile icons are provided by [Social Icons](https://github.com/AcademiaInk/jekyll-theme-academia-icons):

- [Blog](https://github.com/AcademiaInk/jekyll-theme-academia-icons#blog)
- [DBLP](https://github.com/AcademiaInk/jekyll-theme-academia-icons#dblp)
- [Google Scholar](https://github.com/AcademiaInk/jekyll-theme-academia-icons#google-scholar)

---

### **Contributor Graph**

Use the [Contributor Graph](https://github.com/AcademicPages/contributor-graph) to visualize contributions by user to the repository.

---

### **GitHub Pages**

GitHub Pages renders content in the repository's `gh-pages` branch. If your repository's settings have not been configured to serve content from that branch, you'll need to change your settings.

---

### **Front Matter**

The front matter of `README.md` is rendered in the HTML `<head>` section of the default layout. If you'd like to include custom HTML in the `<head>` section, you can use the `extra_head` parameter in the front matter.

```yaml
extra_head: |
  <link rel="stylesheet" href="/assets/css/custom.css">
```

---

### **Reference Projects**

This project is based on the following projects:

- [GitHub Pages](https://pages.github.com)
- [Jekyll](https://jekyllrb.com)
- [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)
- [Just the Docs](https://just-the-docs.com)

---

### **Maintainer**

- [Academic Pages](https://github.com/academicpages)

---

### **Logo**

The logo is provided by [AcademiaInk](https://github.com/AcademiaInk/jekyll-theme-academia-icons).

---

### **Contributing**

- All changes to files should follow the [Contributing Guide](https://github.com/academicpages/academicpages.github.io/wiki/Contributing-Guide)
- Create issues and pull requests with a clear description of the changes being made
- Before submitting a pull request, make sure the changes are valid by running the test suite

---

### **Technical Details**

- **Ruby** (tested on Ruby 2.3.0 - 2.7.6)
- **RubyGems** (tested on RubyGems 3.0.3 - 3.2.22)
- **Jekyll** (tested on Jekyll 3.5.2 - 4.3.4)

---

### **Credits**

The original project was created by [bryanbraun](https://github.com/bryanbraun) in 2017. The original repository can be found at [GitHubPages/start](https://github.com/pages-themes/start). This project has been forked and modified by multiple contributors.

---

### **Citation**

If you use this template for your own website, please cite the template as follows:

```bibtex
@misc{academicpages2020,
  title = {Academic Pages},
  author = {{Academic Pages}},
  howpublished = {\url{https://academicpages.github.io}},
  year = {2020}
}
```

---

### **Contributing**

- [Contributor Covenant](https://contributor-covenant.org/)
- Read the [Code of Conduct](https://github.com/academicpages/academicpages.github.io/blob/master/CODE_OF_CONDUCT.md) before contributing

---

### **Bug Reports**

If you've found a bug, please open an issue with a detailed description of the issue, steps to reproduce the bug, and the version of the template you're using.

---

### **Help**

See the [guide](https://academicpages.github.io/markdown/) for more information about how to use the template. If you need help, you can:

- [open an issue](https://github.com/academicpages/academicpages.github.io/issues/new)
- [start a discussion](https://github.com/academicpages/academicpages.github.io/discussions)

---

### **Knowledge Base**

The [knowledge base](https://github.com/academicpages/academicpages.github.io/wiki) contains answers to common questions about the template.

---

### **Translations**

The template is available in several languages. To change the language, edit the `lang` variable in `_config.yml` (e.g. `lang: zh-CN` for Simplified Chinese, `lang: zh-TW` for Traditional Chinese). If you'd like to contribute a translation, please open a pull request.

---

### **Sponsors**

Support this project with a financial contribution. The project is funded by GitHub.

---

### **Maintainer**

The project is maintained by GitHub.

---

### **Development**

The project is developed by GitHub.

---

### **License**

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

### **Contributing**

Read the [guide](https://github.com/academicpages/academicpages.github.io/wiki/Contributing-Guide) for more information about contributing to the project.

---

### **Artwork License**

The artwork (logo, icons, illustrations, etc.) is licensed under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

---

### **Copyright**

Copyright (c) 2019 GitHub. All rights reserved.

---

### **Security**

Please report any security issues to [security@github.com](mailto:security@github.com).

---

### **Branding**

Use the GitHub brand resources to learn about how to use and share GitHub.

---

### **Trademark**

"GitHub" and other GitHub product names are trademarks of GitHub, Inc.

---

### **About**

Visit the GitHub company website for more information about the project.
