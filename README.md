# SnW Group Pet Store

A simple multi-page website that showcases a fictional pet shop, built with vanilla HTML and CSS. The landing page (`index.html`) highlights product categories, promotions, and quick access to the support, account, and category pages that live inside the `Inside Webpage ` directory.

## Features
- Multi-section home page with hero, category cards, highlights, and testimonials.
- Dedicated species pages (`hamster.html`, `cat.html`, `dog.html`, `fish.html`, `bird.html`) plus About Us, Support, Category, and user-profile flows.
- Shared styling via `PetShop.css` plus supplemental CSS files for each internal page.
- Local assets kept in `Images ` and `Video` to keep the markup clean and easy to update.

## Project Structure
```
SnW-Group-Project-Pet-Store-
├── index.html            # Landing page that links to all inner pages
├── PetShop.css           # Global styles for the landing page
├── Images /              # Logos, hero images, icons, etc.
├── Video/                # Promotional or background video clips
└── Inside Webpage /      # Inner pages + per-page CSS
    ├── AboutUS.html / .css
    ├── Support.html / .css
    ├── Category.html / .css
    ├── Userid.html / .css
    ├── newid.html / .css
    ├── form.css          # Shared form styles
    └── bird|cat|dog|fish|hamster.html
```

> Note: Some folder names include a trailing space (`Images `, `Inside Webpage `, `Website Code `). Keep that spacing intact when running shell commands or renaming files.

## Getting Started
1. Clone or download this repository.
2. Open `index.html` in your browser to explore the landing page.
3. Use the navigation bar or the cards/buttons on the page to visit the inner pages stored in `Inside Webpage `.

## Customization
- Update text/links directly in the HTML files.
- Replace visuals by dropping new assets inside `Images ` (make sure the filenames match the `src` attributes).
- Extend the layout by editing `PetShop.css` or the page-specific CSS files inside `Inside Webpage `.

## Contributing
Feel free to open issues or submit pull requests with improvements. When contributing, keep the codebase HTML/CSS-only (no build tooling) so that pages stay easy to open directly in a browser.
