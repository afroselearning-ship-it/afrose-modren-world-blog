# Static Blog for GitHub Pages

A modern, minimalist, and mobile-responsive static blog optimized for GitHub Pages. No build steps or server-side dependencies required!

## Features

- Works out-of-the-box on GitHub Pages
- Clean, production-ready HTML/CSS/JS
- Mobile-first, minimalist design
- Simple system for adding new posts (`posts/` folder, Markdown supported)
- Portfolio-quality layout
- Relative paths for all assets and links

---

## 🚀 Quick Start

1. **Clone or Fork This Repo**

   ```bash
   git clone https://github.com/your-username/your-blog.git
   cd your-blog
   ```

2. **Add Blog Posts**

   - Place your posts as Markdown (`.md`) or HTML (`.html`) files in the `posts/` folder.
   - Follow the sample post format in `posts/sample-post.md`.
   - Posts must include a frontmatter header for title and date (see below).

3. **Push to GitHub**

   - Commit your changes and push to your repo's `main` branch.
   - Go to your repo -> Settings -> Pages, and set source to `main` branch (root or `/docs` if preferred).

4. **Visit Your Blog**

   - Your site will be live at `https://your-username.github.io/your-blog/`

---

## 📝 Adding New Posts

1. **Create a file in `posts/`**, e.g., `posts/my-first-post.md`
2. **Use this frontmatter at the top:**

   ```
   ---
   title: My First Post
   date: 2025-10-03
   ---
   ```

3. **Write in Markdown** below the frontmatter.

4. **Commit and push.** The post will appear on your homepage automatically.

---

## 🗂 Folder Structure

```
/
├── index.html         # Blog homepage
├── post.html          # Template for displaying posts
├── styles.css         # All custom CSS
├── script.js          # Main JS logic (loading posts, navigation)
├── posts/             # Your blog posts (Markdown or HTML)
│   ├── sample-post.md
│   └── ...more-posts...
├── assets/            # Images or other assets
│   └── ...
└── README.md
```

---

## ✨ Customization

- Edit `styles.css` for branding/colors/fonts.
- Add your avatar/logo in `assets/` and update `index.html` if desired.
- Navigation and metadata are all managed in `index.html` and `script.js`.

---

## 💡 Notes

- All links use **relative paths** for GitHub Pages compatibility.
- No build steps or dependencies required.
- Supports Markdown posts with simple YAML frontmatter parsing (JS-based).

---