<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Amora – The Coffee Shop README</title>
  <style>
    body { font-family: Arial, sans-serif; line-height: 1.6; margin: 2rem; }
    h1, h2, h3 { color: #b2744c; }
    a { color: #b2744c; text-decoration: none; }
    a:hover { text-decoration: underline; }
    code { background: #f4f4f4; padding: 2px 4px; border-radius: 4px; }
    pre { background: #f4f4f4; padding: 1rem; border-radius: 4px; overflow-x: auto; }
    nav ul { list-style: none; padding-left: 0; }
    nav li { margin: 0.5rem 0; }
    section { margin-bottom: 2rem; }
    footer { margin-top: 2rem; font-size: 0.9rem; color: #555; }
  </style>
</head>
<body>

  <header>
    <h1>Amora – The Coffee Shop</h1>
    <p><strong>Amora</strong> is a static, responsive coffee shop website built using HTML5, CSS3, and Bootstrap 5.</p>
  </header>

  <nav>
    <h2>📋 Table of Contents</h2>
    <ul>
      <li><a href="#live-demo">Live Demo</a></li>
      <li><a href="#features">Features</a></li>
      <li><a href="#getting-started">Getting Started</a></li>
      <li><a href="#usage">Usage</a></li>
      <li><a href="#file-structure">File Structure</a></li>
      <li><a href="#technologies">Technologies</a></li>
      <li><a href="#author">Author</a></li>
      <li><a href="#license">License</a></li>
    </ul>
  </nav>

  <section id="live-demo">
    <h2>🔗 Live Demo</h2>
    <p>Deployed via GitHub Pages: <code>https://ks-fsdev.github.io/coffee-shop/</code></p>
  </section>

  <section id="features">
    <h2>✨ Features</h2>
    <ul>
      <li>Responsive layout (desktop, tablet, mobile)</li>
      <li>Full-page hero section with CTA button</li>
      <li>About Us section with image and description</li>
      <li>Product menu grid showcasing items with images, prices, and ratings</li>
      <li>Product showcase section</li>
      <li>Gallery displaying ambiance and offerings</li>
      <li>Contact form with name, email, phone fields</li>
      <li>Blog previews (title, date, excerpt)</li>
      <li>Footer with social media links and credits</li>
    </ul>
  </section>

  <section id="getting-started">
    <h2>🚀 Getting Started</h2>
    <h3>🛠 Prerequisites</h3>
    <ul>
      <li>Modern web browser (Chrome, Firefox, Edge, Safari)</li>
      <li>Internet connection to load Bootstrap, Google Fonts, and Font Awesome</li>
    </ul>
    <h3>📥 Installation</h3>
    <pre><code>git clone https://github.com/ks-fsdev/coffee-shop.git
cd coffee-shop
# Open index.html in your browser
</code></pre>
  </section>

  <section id="usage">
    <h2>⚙️ Usage</h2>
    <ul>
      <li>Click the <strong>Shop Now</strong> button in the hero to browse products.</li>
      <li>Navigate through sections using the top menu links.</li>
      <li>Hover over cards for subtle lift animations.</li>
      <li>Fill out the contact form and send your message.</li>
      <li>Explore blog previews and click <strong>Read More</strong> for details.</li>
    </ul>
  </section>

  <section id="file-structure">
    <h2>📂 File Structure</h2>
    <pre><code>coffee-shop/
├── index.html       # Main HTML file
├── style.css        # Custom CSS stylesheet
├── images/          # Image assets (.avif, .jpg, .png)
│   ├── logo.png
│   ├── bc3.jpg
│   ├── coffee2.avif
│   └── ...
└── .vscode/         # VS Code settings
    └── settings.json
</code></pre>
  </section>

  <section id="technologies">
    <h2>🛠️ Technologies</h2>
    <ul>
      <li>HTML5</li>
      <li>CSS3</li>
      <li>Bootstrap 5</li>
      <li>Font Awesome</li>
      <li>Google Fonts</li>
    </ul>
  </section>

  <footer id="author">
    <h2>👩‍💻 Author</h2>
    <p><strong>Khushi Srivastava</strong><br>
    GitHub: <a href="https://github.com/ks-fsdev">https://github.com/ks-fsdev</a></p>
    <h2 id="license">📄 License</h2>
    <p>Distributed under the <a href="LICENSE">MIT License</a>.</p>
  </footer>

</body>
</html>
