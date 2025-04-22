# Static Blog Website

A simple, modern static blog website built with HTML, CSS, and JavaScript.

## Features

- Clean, responsive design
- Modern typography using Inter font
- Smooth scrolling navigation
- Blog post grid layout
- Mobile-friendly design

## Getting Started

1. Clone this repository
2. Open `index.html` in your browser to view the website
3. Customize the content in `index.html` to add your own blog posts
4. Modify `styles.css` to change the appearance
5. Add your own JavaScript functionality in `script.js`

## Customization

### Adding New Blog Posts

To add a new blog post, copy the following template and add it to the `posts-grid` section in `index.html`:

```html
<article class="post-card">
    <div class="post-content">
        <h4>Your Post Title</h4>
        <p class="post-date">March 19, 2024</p>
        <p class="post-excerpt">Your post excerpt goes here...</p>
        <a href="#" class="read-more">Read More</a>
    </div>
</article>
```

### Changing Colors

The color scheme can be modified by changing the CSS variables in the `:root` selector in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --text-color: #1f2937;
    --background-color: #ffffff;
    --secondary-background: #f3f4f6;
}
```

## License

This project is open source and available under the MIT License. 