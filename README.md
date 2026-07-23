# Luo Wenbo - Academic Personal Website

This is the source code for my academic personal website, hosted on GitHub Pages.

## 🌐 Website

[https://luomrme-cpu.github.io](https://luomrme-cpu.github.io)

## 📋 Features

- Home page with personal introduction
- CV / Resume page (with PDF download)
- Research interests page
- Publications page (with PDF links for papers)
- Teaching experience page
- Contact information

## 🛠️ Technology Stack

- **GitHub Pages** - Free hosting
- **Jekyll** - Static site generator
- **Markdown** - Content writing
- **Minima** - Jekyll theme

## 📁 Folder Structure

```
.
├── _config.yml              # Website configuration
├── index.md                 # Home page
├── cv.md                    # CV page
├── research.md              # Research page
├── publications.md          # Publications page
├── teaching.md              # Teaching page
├── contact.md               # Contact page
├── assets/
│   ├── pdfs/                # Store PDF files (CV, papers, etc.)
│   ├── images/              # Store images (profile photo, etc.)
│   └── css/                 # Custom styles
├── _layouts/                # Page layouts
├── _includes/               # Reusable components
└── Gemfile                  # Ruby dependencies
```

## 🚀 How to Update

### Adding a PDF File

1. Place your PDF file in `assets/pdfs/`
2. Link to it in Markdown: `[PDF](assets/pdfs/your-file.pdf)`

### Updating Content

1. Edit the corresponding `.md` file
2. Commit and push to GitHub
3. GitHub Pages will automatically rebuild the website

## 📤 Deploy to GitHub

### First Time Setup

1. Create a repository on GitHub named `YOUR-USERNAME.github.io`
2. Run these commands:

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
git push -u origin main
```

### Subsequent Updates

```bash
git add .
git commit -m "Update: description of changes"
git push
```

## 📝 Customization

- Edit `_config.yml` to change website title, author info, and navigation
- Edit Markdown files (`.md`) to update page content
- Add your photo to `assets/images/profile.jpg`
- Add your CV PDF to `assets/pdfs/cv.pdf`

## 📄 License

This is my personal website. Feel free to use the structure as a template for your own academic website.
