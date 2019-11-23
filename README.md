# Running the website

The site is rendered with github pages and Jekyll.  To locally build/test the site, follow the getting started instructions here: https://jekyllrb.com/docs/ .  In short, you will need to install ruby, and then the gems for "bundler" (which handles versions, etc found in the Gemfile) and "jekyll" (which handles the conversion of markdown to html.

To render locally, clone this repo, run `bundle exec jekyll serve`.

Changes will be applied automatically by GitHub pages after each push.

###  `docs` folder
Copies of HTML files from various analyses can be put here for rendering. The `pre-commit.sh` script can be used to copy the relavent files from the relavent repositories.


-------------------------
You can use the [editor on GitHub](https://github.com/FEMLab/FEMLab.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/FEMLab/FEMLab.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
