# Kiru's Blog

A personal blog and portfolio website built with Hugo and the Toha theme.

## 🚀 Features

- Modern and responsive design
- Portfolio section to showcase your work
- Clean and minimal interface
- Built with Hugo and Toha theme v4

## 🛠️ Prerequisites

- Hugo Extended version 0.142.0 or higher
- Git
- Node.js (for theme dependencies)

## 🏗️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mkiruba/kiru.github.io.git
   cd kiru.github.io
   ```

2. Install theme dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   hugo server -D
   ```

## 📁 Project Structure

```
kiru.github.io/
├── content/          # Your content files
├── static/          # Static files (images, CSS, JS)
├── config.yaml      # Site configuration
└── themes/          # Theme files (managed by Hugo modules)
```

## ⚙️ Configuration

The site is configured using `config.yaml`. Key settings include:

- Base URL: https://hugo-toha.github.io
- Language: English
- Features enabled:
  - Portfolio section
  - Blog posts (currently disabled)
  - Table of contents (currently disabled)

## 🚀 Deployment

The site is deployed to GitHub Pages. The deployment process is automated through GitHub Actions.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Hugo](https://gohugo.io/) - The static site generator
- [Toha Theme](https://github.com/hugo-toha/toha) - The theme used for this site