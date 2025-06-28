# My Hugo Website

This is a Hugo website hosted on Netlify using the **PaperMod** theme.

## Theme

The site uses the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme, which provides:

- Fast, responsive design
- Light/Dark mode toggle
- Table of contents for posts
- Search functionality
- Social media integration
- Reading time and word count
- SEO optimization

## Local Development

To run the site locally:

1. Make sure you have Hugo installed (version 0.146.0 or higher)
2. Clone this repository
3. Run `hugo server` to start the development server
4. Visit `http://localhost:1313` in your browser

## Content Structure

- `content/posts/` - Blog posts
- `content/about/` - About page
- `archetypes/` - Content templates
- `config.yaml` - Site configuration

## Creating New Content

To create a new blog post:

```bash
hugo new posts/my-new-post.md
```

## Customization

The theme can be customized through the `config.yaml` file. Key settings include:

- Social media links
- Menu configuration
- Theme appearance
- Search functionality

## Deployment

The site is automatically deployed to Netlify when changes are pushed to the main branch.

## Requirements

- Hugo Extended version 0.146.0 or higher
- Git (for theme submodule) 