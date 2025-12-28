# jsonresume-theme-kendall-projects-first

A [JSON Resume](https://jsonresume.org/) theme based on [Kendall](https://github.com/LinuxBozo/jsonresume-theme-kendall) with **Projects section displayed before Work Experience**.

Perfect for developers, portfolio-focused professionals, and anyone who wants to highlight their projects prominently.

## What's Different?

This theme is a fork of the excellent [jsonresume-theme-kendall](https://github.com/LinuxBozo/jsonresume-theme-kendall) by M. Adam Kendall with the following changes:

- **Projects section moved before Work Experience** - Great for showcasing side projects, open source contributions, or portfolio work
- **Enhanced Projects display** - Projects now show:
  - Start/End dates (optional)
  - Roles
  - Highlights
  - Keywords as badges
- All original Kendall theme features preserved

## Section Order

1. About (Summary)
2. **Projects** (moved up!)
3. Work Experience
4. Awards
5. Volunteer
6. Education (sidebar)
7. Skills (sidebar)
8. Languages (sidebar)
9. Interests (sidebar)
10. References (sidebar)

## Installation

```bash
npm install jsonresume-theme-kendall-projects-first
```

## Usage

### With resume-cli

```bash
npm install -g resume-cli
resume export resume.html --theme kendall-projects-first
resume export resume.pdf --theme kendall-projects-first
```

### Preview locally

```bash
resume serve --theme kendall-projects-first
```

## Example resume.json Projects Section

```json
{
  "projects": [
    {
      "name": "My Awesome Project",
      "description": "A brief description of what the project does",
      "highlights": [
        "Built with React and Node.js",
        "Used by 1000+ users"
      ],
      "keywords": ["React", "Node.js", "MongoDB"],
      "startDate": "2023-01-01",
      "endDate": "2023-06-01",
      "url": "https://github.com/username/project",
      "roles": ["Lead Developer"]
    }
  ]
}
```

## Supported Profiles

The theme supports these social profiles with icons:

- GitHub, GitLab, Bitbucket
- LinkedIn, Twitter/X, Facebook
- Stack Overflow, CodePen
- YouTube, Vimeo, Behance, Dribbble
- And many more (auto-detected from FontAwesome)

## Credits

- Original theme: [jsonresume-theme-kendall](https://github.com/LinuxBozo/jsonresume-theme-kendall) by M. Adam Kendall
- Fork maintained by: [Murat Topcu](https://github.com/MuratTopcu)

## License

MIT License - See [LICENSE](LICENSE) file for details.

This is a fork of jsonresume-theme-kendall, original work by M. Adam Kendall.
