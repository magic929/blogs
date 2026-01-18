# Blogs

A documentation and memo repository powered by GitHub Pages.

## 🌐 View the Site

Visit the published site at: [https://magic929.github.io/blogs](https://magic929.github.io/blogs)

## 📝 About

This repository uses GitHub Pages with Jekyll to create a simple documentation site for writing memos, notes, and blog posts.

## 🚀 Quick Start

### Writing Documentation

1. Create new markdown files in the `docs/` directory
2. Add front matter to each file:
   ```yaml
   ---
   layout: default
   title: Your Page Title
   ---
   ```
3. Write your content using Markdown
4. Commit and push to GitHub

### Local Development

To run the site locally:

```bash
# Install dependencies
bundle install

# Run Jekyll server
bundle exec jekyll serve

# Visit http://localhost:4000 in your browser
```

## 📂 Structure

```
.
├── _config.yml          # Jekyll configuration
├── index.md             # Home page
├── docs/                # Documentation files
│   ├── getting-started.md
│   └── writing-docs.md
├── Gemfile              # Ruby dependencies
└── .github/
    └── workflows/
        └── jekyll.yml   # GitHub Actions deployment
```

## 🛠️ Configuration

The site is configured in `_config.yml`. You can customize:

- Site title and description
- Theme (currently using Cayman theme)
- Navigation and collections
- Build settings

## 📚 Resources

- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/)

## 📄 License

This repository is for personal documentation and memos. 
