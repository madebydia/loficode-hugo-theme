# LofiCode Hugo Theme

Built by [@madebydia](https://x.com/madebydia)

A cozy, lo-fi inspired Hugo theme perfect for developers and creatives who want to create a warm, inviting blog with a retro aesthetic and modern functionality.

![LofiCode Theme Screenshot](https://raw.githubusercontent.com/raisingpixels/loficode-hugo-theme/master/images/screenshot.png)

## ✨ Features

- **🎵 Ambient Sounds**: Built-in ambient sound player with coffee shop, rain, and fireplace sounds
- **🌙 Dark/Light Mode**: Automatic theme detection with manual toggle
- **📱 Fully Responsive**: Beautiful on all devices from mobile to desktop
- **🔍 Live Search**: Real-time search functionality across all posts
- **📖 Table of Contents**: Auto-generated TOC for blog posts
- **🎨 Syntax Highlighting**: Beautiful code blocks with copy functionality
- **☕ Coffee Theme**: Reading time displayed with coffee cups
- **🚀 SPA Navigation**: Smooth single-page app experience
- **♿ Accessible**: WCAG compliant with proper ARIA labels
- **⚡ Performance**: Optimized for speed and SEO

## 🎨 Design Philosophy

LofiCode embraces the cozy, nostalgic feeling of lo-fi aesthetics while maintaining modern web standards. The theme features:

- Warm, gradient backgrounds reminiscent of sunset vaporwave
- Retro-inspired typography with modern readability
- Subtle animations and hover effects
- Coffee-themed reading indicators
- Ambient sound integration for a cozy coding atmosphere

## 🚀 Quick Start

### 1. Install the Theme

```bash
# Clone into your Hugo site's themes directory
git clone https://github.com/madebydia/loficode-hugo-theme.git themes/loficode

# Or add as a Git submodule
git submodule add https://github.com/madebydia/loficode-hugo-theme.git themes/loficode
```

### 2. Configure Your Site

Add the theme to your `hugo.toml`:

```toml
theme = "loficode"

[params]
  description = "Your site description"

  [params.author]
    name = "Your Name"
    image = "images/profile.png"

  # Profile section
  [params.profile]
    name = "Your Name"
    tagline = "Your tagline here"
    photo = "/images/profile.png"

  # Social links - Supported platforms: github, twitter, linkedin, email, mastodon, youtube, instagram, facebook
  [params.social]
    github = "madebydia"
    twitter = "madebydia"
    # linkedin = "your-linkedin-username"
    # email = "your-email@example.com"
    # mastodon = "https://mastodon.social/@yourusername"
    # youtube = "https://youtube.com/@yourusername"
    # instagram = "your-instagram-username"
    # facebook = "your-facebook-username"

# Navigation menu
[[menu.main]]
  name = "About"
  url = "/about/"
  weight = 10

[[menu.main]]
  name = "Contact"
  url = "/contact/"
  weight = 20
```

### 3. Create Content

```bash
# Create your first post
hugo new posts/my-first-post.md
```

### 4. Run Your Site

```bash
hugo server -D
```

## 📁 Content Structure

```
content/
├── _index.md          # Homepage content
├── about.md           # About page
├── contact.md         # Contact page
└── posts/             # Blog posts
    ├── post-1.md
    └── post-2.md
```

## 🎵 Ambient Sounds

The theme includes three ambient sound options:

- **☕ Coffee Shop**: Gentle café ambience
- **🌧️ Rain**: Soft rain sounds
- **🔥 Fireplace**: Crackling fire

Sounds can be toggled on/off and volume adjusted via the bottom control bar.

## 🔗 Social Links

LofiCode supports multiple social media platforms with beautiful icons. Add any combination of the following to your `hugo.toml`:

### Supported Platforms

- **GitHub** - `github = "your-username"`
- **Twitter/X** - `twitter = "your-username"`
- **LinkedIn** - `linkedin = "your-linkedin-username"`
- **Email** - `email = "your-email@example.com"`
- **Mastodon** - `mastodon = "https://mastodon.social/@yourusername"`
- **YouTube** - `youtube = "https://youtube.com/@yourusername"`
- **Instagram** - `instagram = "your-instagram-username"`
- **Facebook** - `facebook = "your-facebook-username"`

### Configuration Example

```toml
[params.social]
  github = "madebydia"
  twitter = "madebydia"
  linkedin = "your-linkedin-username"
  email = "contact@example.com"
```

Only the platforms you configure will be displayed. The theme automatically handles the appropriate URL formatting and icons for each platform.

## 🎨 Customization

### Colors and Themes

The theme uses CSS custom properties for easy customization. Override these in your own CSS:

```css
:root {
  --accent-primary: #FF006B;
  --accent-secondary: #00CED1;
  --accent-tertiary: #FF7F50;
  /* ... more variables */
}
```

### Front Matter Options

```yaml
---
title: "Your Post Title"
subtitle: "Optional subtitle"
date: 2025-01-01
tags: ["hugo", "theme", "lofi"]
featured: true  # Highlights the post
mood: "cozy"    # Adds a mood badge
---
```

### Shortcodes

#### Coffee Break

Add cozy breaks in your content:

```markdown
{{< coffee-break title="Take a Break" >}}
Time for a coffee break! ☕ Grab your favorite mug and enjoy a moment of calm.
{{< /coffee-break >}}
```

## 📱 Responsive Design

LofiCode is built mobile-first and looks great on:

- 📱 Mobile phones (320px+)
- 📱 Tablets (768px+)
- 💻 Laptops (1024px+)
- 🖥️ Desktops (1200px+)

## ⚡ Performance

- Optimized CSS with minimal dependencies
- Lazy loading for images
- Efficient JavaScript with no heavy frameworks
- Fast search implementation
- Optimized web fonts

## 🔧 Development

### Prerequisites

- Hugo Extended v0.112.0 or later
- Node.js (for development tools)

### Local Development

```bash
# Clone the repository
git clone https://github.com/madebydia/loficode-hugo-theme.git
cd loficode-hugo-theme

# Install dependencies (if any)
npm install

# Run Hugo server
hugo server -D
```

## 🎵 Sound Credits

The ambient sounds included with this theme are provided under Creative Commons licenses:

- **Soft Rain Loop** by _lynks - [Freesound](https://freesound.org/s/595717/) - License: Creative Commons 0
- **Fire.wav** by TheBoatman - [Freesound](https://freesound.org/s/347706/) - License: Attribution 4.0
- **Cafe 1** by Rylius - [Freesound](https://freesound.org/s/165280/) - License: Attribution 4.0

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Guidelines

1. Follow the existing code style
2. Test your changes thoroughly
3. Update documentation as needed
4. Ensure accessibility standards are maintained

## 📄 License

This theme is released under the [MIT License](LICENSE).

---

Made with ☕ and 💜 for the Hugo community.
