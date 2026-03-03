# Copilot Instructions

## Project Overview
This repository hosts the "First Party or No Party" advocacy website at firstpartyornoparty.wwn.se (previously firstpartyornoparty.org), which promotes serving ads and tracking from first-party domains rather than third-party services. The site is built with Hugo and hosted on Cloudflare Pages, automatically deployed from the master branch.

## Tech Stack
- **Static Site Generator**: Hugo
- **Theme**: Terminal theme (located in `themes/terminal`)
- **Configuration**: TOML format (`config.toml`)
- **Content**: Markdown files in `content/` directory
- **Hosting**: Cloudflare Pages (auto-deploys from master branch)

## Project Structure
- `content/` - Markdown content files for the website
- `themes/terminal/` - Hugo theme (Terminal theme)
- `config.toml` - Hugo site configuration
- `archetypes/` - Hugo content templates
- `functions/` - Cloudflare Pages functions (if any)
- `.github/workflows/` - GitHub Actions workflows for CI/CD

## Content Guidelines
- All content files should be in Markdown format
- Content should be clear, concise, and focused on the first-party vs third-party messaging
- Keep the advocacy tone professional and informative
- Maintain consistency with existing content style

## Configuration Standards
- Use TOML format for configuration files
- Follow the existing structure in `config.toml`
- Theme color is set to "blue"
- Language is English (en-us)

## Deployment
- The site is automatically deployed to Cloudflare Pages from the master branch
- No manual build or deployment steps are required
- Changes to master branch will trigger automatic deployment

## Contributing
- Feel free to improve the site's message and content
- Open issues or pull requests for contributions
- Contact: Open a [GitHub Issue](https://github.com/NicklasAndersson/FPoNP/issues)
