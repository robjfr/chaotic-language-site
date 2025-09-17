# Chaotic Language Site

Hugo-based website for chaoticlanguage.com featuring research articles on chaos theory, linguistics, and complex systems.

## Features

- **Hugo Static Site Generator** with custom theme
- **Netlify CMS** for easy content management
- **Responsive Design** optimized for articles and media
- **Content Types**: Articles, Videos, Podcasts
- **Mathematical Notation** support
- **SEO Optimized**

## Content Structure

- `content/post/` - Research articles
- `content/videos/` - Video content with embed support
- `content/podcasts/` - Podcast episodes with external links

## Development

```bash
# Install Hugo (extended version)
# Clone this repository
git clone https://github.com/robjfr/chaotic-language-site.git
cd chaotic-language-site

# Run development server
hugo server

# Build for production
hugo --gc --minify
```

## Deployment

This site is configured for Netlify deployment:

1. Connect repository to Netlify
2. Enable Netlify Identity for CMS access
3. Configure custom domain: chaoticlanguage.com
4. Access CMS at: chaoticlanguage.com/admin

## Content Management

- **Admin Interface**: `/admin` (requires Netlify Identity)
- **Direct Editing**: Edit Markdown files in `content/` directory
- **Media**: Upload images via CMS or place in `static/images/uploads/`

## Technologies

- Hugo 0.115.4+
- Netlify CMS
- Custom responsive theme
- MathJax for mathematical notation