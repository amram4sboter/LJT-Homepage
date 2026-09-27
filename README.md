# Academic Pages

This is a clean and modern GitHub Pages template for personal academic websites, designed and maintained by GitHub.

**Key features**:
- Responsive for mobile, tablet and desktop
- Clean design with minimal colors
- Easy to customize and extend

## View the example site

Visit the example site: [academicpages.github.io](https://academicpages.github.io)

## Get started

### Setting up your own site

#### Fork the template

1. Click the **"Use this template" button** to create a new repository with this template
2. **Delete the old fork** (if any)
3. Set **site settings**:

```yaml
site_name: "Your Name"
url: https://yourusername.github.io # the base hostname & protocol for your site e.g. "https://[your GitHub username].github.io",
                                                           # or if you already have some other page hosted on Github then use "https://[your GitHub username].github.io/[Your Repo Name]"
baseurl: "" # the subpath of your site, e.g. "/blog"
repository: "yourusername/yourusername.github.io"
theme: academicpages
```

#### Add your content

1. **Publications**: Add your publications in markdown format
2. **Research Interests**: Write about your research interests and keywords
3. **Experience**: Timeline-based entry of your experiences
4. **Skills**: Add your categorized skills with visual indicators
5. **Contact Info**: Add your contact details

#### Customize the theme

1. **Theme colors**: Modify the theme colors in _config.yml
2. **Fonts**: Customize the fonts used in the site
3. **Layouts**: Modify the layout files to change the structure of the site
4. **Templates**: Create custom templates for your pages

## Build and run locally

### Using Jekyll

1. Install Jekyll:

```bash
bundle install
```

2. Run the development server:

```bash
bundle exec jekyll serve
```

3. Visit your site at [localhost:4000](http://localhost:4000)

### Using Docker

1. Build the Docker image:

```bash
docker build -t academicpages .
```

2. Run the Docker container:

```bash
docker run -p 4000:4000 academicpages
```

3. Visit your site at [localhost:4000](http://localhost:4000)

### Using GitHub Pages

1. Deploy your site to GitHub Pages
2. Visit your site at [yourusername.github.io](https://yourusername.github.io)

## Examples

The Academic Pages project includes an example site with the following pages:
- Homepage
- Publications
- Research
- Experience
- Skills
- Contact

### Publication categories

- **NeurIPS 2023**: Conference
- **ICML 2024**: Conference
- **EMNLP 2024**: Conference

### Research interests

- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models
- LLM Truthfulness and Interpretability

### Experience

- **February 2025 - Present**: Research Intern at MINIMAX
- **June 2024 - September 2024**: Research Intern at Tencent WXG
- **June 2023 - December 2023**: Research Intern at Shanghai AI Lab

### Skills

- **Programming**: Python, C++, PyTorch, TensorFlow
- **Research**: Machine Learning, Natural Language Processing
- **Tools**: Git, GitHub Pages, Jekyll, Markdown

### Contact

- **Email**: jliugi@connect.ust.hk
- **GitHub**: https://github.com/Vicent0205
- **Google Scholar**: https://scholar.google.com/citations?user=tbK9jl4AAAAJ
- **X (Twitter)**: @junteng88716710

## Project status

The Academic Pages project is actively maintained by the GitHub community. Contributions are welcome!

## Contribution

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test your changes
5. Open a pull request

### Release process

1. Create a new release
2. Update the CHANGELOG
3. Tag the release
4. Push the release

### Bug report process

1. Check the issue tracker
2. If the bug hasn't been reported, create a new issue
3. Provide detailed information about the bug
4. Include steps to reproduce the bug
5. Include screenshots (if applicable)

### Feature request process

1. Check the issue tracker
2. If the feature hasn't been requested, create a new issue
3. Describe the feature request in detail
4. Include use cases for the feature

## License

This project is licensed under the MIT License - see the LICENSE file for details.

Copyright (c) 2022-2023 GitHub
