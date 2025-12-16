# GCWokeUp.github.io

Personal website and tech blog for Gino Paul Mendoza Capio - Software Developer specializing in full-stack web development and mobile applications.

🌐 **Live Site**: [https://gcwokeup.github.io](https://gcwokeup.github.io)

## About This Site

This is my personal portfolio and blog where I share my journey as a software engineer, showcase projects, and write about technical topics. Built with Jekyll and the Hacker theme, hosted on GitHub Pages.

### What You'll Find Here

- **Blog**: Technical articles and insights on software development
- **Experience**: My professional journey and work history
- **Portfolio**: Featured projects and technical skills with embedded demos
- **About**: My story, philosophy, and community involvement

## Tech Stack

- **Static Site Generator**: [Jekyll](https://jekyllrb.com/) 3.10.0
- **Theme**: [Hacker Theme](https://github.com/pages-themes/hacker)
- **Hosting**: [GitHub Pages](https://pages.github.com/)
- **Languages**: Ruby, HTML, CSS (SCSS), Liquid templating

## Features

- ✨ Clean, terminal-inspired design with Hacker theme
- 📱 Fully responsive design optimized for mobile
- 📊 Responsive navbar with active page highlighting
- 📝 Blog with post listings and excerpts
- 💼 Comprehensive experience timeline with 5 speaking engagements
- 🚀 Project showcase with impact metrics and embedded video demos
- 🎨 Custom SCSS styling
- 📖 Easy-to-read typography
- 🔗 Social links (GitHub, LinkedIn, Instagram)

## Local Development

### Prerequisites

- Ruby 3.x
- Bundler
- Git

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/gcwokeup/gcwokeup.github.io.git
   cd gcwokeup.github.io
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run the development server**
   ```bash
   bundle exec jekyll serve --no-watch --host 127.0.0.1
   ```

4. **View the site**
   
   Open your browser to [http://127.0.0.1:4000](http://127.0.0.1:4000)

### Building the Site

To build the site without running a server:

```bash
bundle exec jekyll build
```

The compiled site will be in the `_site` directory.

## Project Structure

```
├── _config.yml           # Site configuration
├── _layouts/            
│   └── default.html      # Custom layout template
├── _posts/              
│   └── *.markdown        # Blog posts
├── assets/
│   └── css/
│       └── style.scss    # Custom styles
├── about.markdown        # About page with speaking engagements
├── blog.markdown         # Blog archive
├── experience.markdown   # Work experience timeline
├── portfolio.markdown    # Projects & skills with video demos
├── index.markdown        # Landing page
├── Gemfile              # Ruby dependencies
└── README.md            # This file
```

## Writing Blog Posts

Blog posts are written in Markdown and stored in the `_posts` directory.

### Naming Convention

Posts must follow this naming pattern:
```
YYYY-MM-DD-title-of-post.markdown
```

### Post Template

```markdown
---
layout: default
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS -0500
categories: category1 category2
---

Your content here...
```

### Creating a New Post

1. Create a new file in `_posts/` with the correct naming format
2. Add front matter (layout, title, date, categories)
3. Write your content in Markdown
4. Build/serve the site to preview
5. Commit and push to publish

## Customization

### Updating Site Information

Edit `_config.yml`:
```yaml
title: Your Name
description: Your tagline
github_username: yourusername
```

### Modifying Styles

Custom styles are in `assets/css/style.scss`. The file imports the Hacker theme and adds custom CSS on top.

### Changing Navigation

Edit the navbar in `_layouts/default.html`:
```html
<nav class="main-nav">
  <a href="{{ '/page/' | relative_url }}">Page Name</a>
</nav>
```

## Deployment

This site is automatically deployed to GitHub Pages when you push to the `main` branch.

### Deploy Steps

1. **Stage your changes**
   ```bash
   git add .
   ```

2. **Commit with a meaningful message**
   ```bash
   git commit -m "Description of changes"
   ```

3. **Push to GitHub**
   ```bash
   git push origin main
   ```

4. **Wait for deployment**
   
   GitHub Pages will automatically build and deploy your site (usually takes 1-2 minutes)

## Technologies & Skills Showcased

### Languages
- Ruby
- JavaScript
- Swift
- Java
- HTML5/CSS3

### Frameworks
- Ruby on Rails
- React / React Native
- iOS (Swift)
- Spring Framework

### Databases
- PostgreSQL
- MongoDB
- Redis
- Elasticsearch

### Cloud & Tools
- Google Cloud Platform (GCP)
- Amazon Web Services (AWS)
- Heroku
- Firebase
- Git & GitHub

## About Me

I'm a Software Developer at Pixite Inc with nearly a decade of experience building scalable web and mobile applications. I'm passionate about clean code, mentoring developers, and fostering inclusive tech communities.

### Connect With Me

- 💼 [LinkedIn](https://www.linkedin.com/in/ginopaulcapio/)
- 🐙 [GitHub](https://github.com/gcwokeup)
- 📸 [CoolCatsCoding on Instagram](https://www.instagram.com/coolcatscoding/)

## Community

I'm the founder of **CoolCatsCoding**, a collective of learners and software engineers fostering a tech "Each One, Teach One" environment. We meet weekly to collaborate, learn, and support each other's growth.

## License

This project is open source. Feel free to fork it and use it as a template for your own site!

## Acknowledgments

- Built with [Jekyll](https://jekyllrb.com/)
- Theme: [Hacker](https://github.com/pages-themes/hacker) by GitHub
- Hosted on [GitHub Pages](https://pages.github.com/)

---

**Built with ❤️ and Ruby**
