# NguyenAndrew.github.io

Personal website for Andy Nguyen — Software Engineer, Innovator, and Friend.

Live site: [andyln.com](https://andyln.com)

## About

This is the source code for Andy Nguyen's personal website, built with [Jekyll](https://jekyllrb.com/) using the [JBlog](https://alperenbozkurt.net/JBlog) theme and hosted on GitHub Pages.

## Website Sections

| Section | URL | Description |
|---------|-----|-------------|
| Home | `/` | Landing page with profile photo, bio, social links, and site navigation |
| Blog | `/blog/` | Index of all blog posts |
| About | `/about/` | Personal background, career history, and bio |
| Resume | `/resume/` | Redirects to the PDF resume ([andyln-resume.pdf](resume/andyln-resume.pdf)) |
| 404 | `/404` | Custom not-found page with a link to file a GitHub issue |

## Project Structure

```
.
├── _config.yml          # Site configuration (title, bio, social links, plugins)
├── _data/
│   └── navigation.yml   # Navigation menu items and URLs
├── _includes/           # Reusable HTML partials
│   ├── nav.html         # Navigation bar (inner pages)
│   ├── nav-home.html    # Navigation bar (home page)
│   ├── footer.html      # Page footer (inner pages)
│   ├── footer-home.html # Page footer (home page)
│   ├── social-links.html # Social media icon links
│   ├── head.html        # <head> tag (inner pages)
│   ├── head-home.html   # <head> tag (home page)
│   └── ...              # Additional partials (scripts, comments, TOC, etc.)
├── _layouts/            # Page templates
│   ├── home.html        # Home/landing page layout
│   ├── post.html        # Individual blog post layout
│   ├── post-index.html  # Blog index layout
│   ├── page.html        # Generic content page layout
│   └── redirected.html  # Redirect layout (used by Resume)
├── _posts/              # Blog posts in Markdown (YYYY-MM-DD-title.md)
├── _sass/               # SCSS stylesheets
│   ├── variables.scss   # Colors, fonts, and theming variables
│   └── site.scss        # Main stylesheet
├── assets/              # Static assets (images, fonts, CSS, JS)
├── about/
│   └── index.md         # About Me page content
├── blog/
│   └── index.md         # Blog index page front matter
├── resume/
│   ├── index.md         # Resume redirect page
│   └── andyln-resume.pdf# PDF resume
├── index.html           # Home page
├── 404.html             # Custom 404 page
├── CNAME                # Custom domain (andyln.com)
├── Gemfile              # Ruby gem dependencies
└── robots.txt           # Search engine crawl rules
```

## Blog Posts

- [MOD - Take on Successful Software](https://andyln.com/mod-take-on-successful-software/) (2022-04-19)
- [Rune Scimitars and Solutions – Strategically delivering products to your users](https://andyln.com/rune-scimitars-and-solutions/) (2020-11-16)
- [How to Tutor Programmers Efficiently and Effectively](https://andyln.com/how-to-tutor-programmers-efficiently-and-effectively/) (2018-12-27)

## Connect

- GitHub: [NguyenAndrew](https://github.com/NguyenAndrew)
- LinkedIn: [nguyen-andrew](https://www.linkedin.com/in/nguyen-andrew/)

## Built With

- [Jekyll](https://jekyllrb.com/)
- [JBlog Theme](https://alperenbozkurt.net/JBlog)
- [GitHub Pages](https://pages.github.com/)
