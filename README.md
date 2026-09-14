# Clothes Store CMS

A responsive e-commerce storefront for a clothing / retail website, built with HTML, CSS, Bootstrap, JavaScript, jQuery, and reusable front-end plugins.

The project includes a product-focused homepage with navigation, search, responsive mobile menus, promotional sliders, product grids, category filtering, cart links, brand sections, service highlights, and footer navigation.

## Features

- Responsive layout for desktop, tablet, and mobile
- Bootstrap-based grid and components
- Desktop, sticky, and mobile navigation
- Product search interface
- Hero / promotional carousel
- Product cards with pricing and size selection
- Product category filtering
- Quantity controls
- Wishlist and cart UI
- Product detail and cart page links
- Brand / sponsor carousel
- Responsive footer
- Social media links
- Google Fonts integration
- Animation and scrolling effects

## Tech Stack

- HTML5
- CSS3
- Bootstrap
- JavaScript
- jQuery
- Google Fonts
- Font / Flaticon icon assets

### Front-end plugins used

The homepage references the following local JavaScript libraries/plugins:

- jQuery
- jQuery UI
- Bootstrap
- Popper
- Owl Carousel
- MixItUp
- Magnific Popup
- WOW.js
- TouchSpin
- Odometer
- Parallax
- jQuery Countdown
- jQuery Marquee
- jQuery Paroller
- mCustomScrollbar
- Tilt.js
- Custom navigation and site scripts

## Project Structure

Based on the current `index.html`, the project is expected to follow a structure similar to:

```text
clothes-storecms/
├── index.html
├── about.html
├── contact.html
├── shop.html
├── shop-detail.html
├── cart.html
├── services.html
├── service-detail.html
│
├── css/
│   ├── bootstrap.css
│   ├── style.css
│   └── responsive.css
│
├── js/
│   ├── jquery.js
│   ├── jquery-ui.js
│   ├── popper.min.js
│   ├── bootstrap.min.js
│   ├── owl.js
│   ├── mixitup.js
│   ├── magnific-popup.min.js
│   ├── touchspin.js
│   ├── wow.js
│   ├── appear.js
│   ├── odometer.js
│   ├── parallax.min.js
│   ├── jquery.countdown.js
│   ├── jquery.marquee.min.js
│   ├── jquery.paroller.min.js
│   ├── jquery.mCustomScrollbar.concat.min.js
│   ├── tilt.jquery.min.js
│   ├── nav-tool.js
│   ├── backToTop.js
│   └── script.js
│
├── images/
│   ├── clients/
│   ├── icons/
│   ├── main-slider/
│   └── product and promotional images
│
├── fonts/
│   └── local font/icon files
│
├── .gitignore
├── LICENSE
└── README.md
```

> Some linked pages may not yet exist in the repository. The structure above reflects the paths referenced by the current homepage.

## Main Pages

| Page | Purpose |
| --- | --- |
| `index.html` | Main storefront / homepage |
| `about.html` | About page |
| `contact.html` | Contact page |
| `shop.html` | Product listing / shop |
| `shop-detail.html` | Individual product details |
| `cart.html` | Shopping cart |
| `services.html` | Services / category content |
| `service-detail.html` | Service detail content |

## CSS Files

The homepage loads:

```text
css/bootstrap.css
css/style.css
css/responsive.css
```

The responsive stylesheet should contain viewport-specific layout adjustments, while `style.css` contains the primary visual design.

## JavaScript Files

The homepage loads its scripts from the `js/` directory. Keep the existing script order when modifying the project because plugins can depend on jQuery, Popper, Bootstrap, or other libraries loaded before them.

## Image Assets

Keep all front-end image assets inside the `images/` directory and preserve their relative paths.

Examples used by the homepage include:

```text
images/dem.png
images/favicon.png
images/icons/
images/main-slider/
images/clients/
```

When replacing a product, logo, banner, or icon image, either preserve the existing filename or update its corresponding HTML path.

## Local Development

### Option 1: Open directly

For basic front-end development, open:

```text
index.html
```

in a modern browser.

### Option 2: VS Code Live Server

1. Clone the repository.
2. Open the project in Visual Studio Code.
3. Install the **Live Server** extension.
4. Right-click `index.html`.
5. Choose **Open with Live Server**.

### Clone the repository

```bash
git clone https://github.com/preamshah/clothes-storecms.git
cd clothes-storecms
```

## Deployment

Because the current storefront is primarily static HTML/CSS/JavaScript, it can be deployed to:

- Hostinger
- Apache / cPanel hosting
- Netlify
- Cloudflare Pages
- GitHub Pages, if no server-side PHP/backend functionality is required

For traditional hosting, upload the project files while preserving the directory structure.

Example:

```text
public_html/
├── index.html
├── css/
├── js/
├── images/
└── fonts/
```

## Customization

### Change the logo

Update the logo image referenced in the HTML, for example:

```html
<img src="images/dem.png" alt="Store Logo">
```

### Change products

Edit the product cards in `index.html` or the relevant shop page. Update:

- Product image
- Product name
- Price
- Old price
- Available sizes
- Product detail URL

### Change fonts

The homepage currently references Google Fonts including:

- Outfit
- Jost
- Josefin Sans
- Inter
- Roboto

Remove unused font imports if you want to improve page performance.

## Recommended Improvements

Before production deployment, consider:

- Replacing placeholder product and category content
- Adding meaningful image `alt` attributes
- Correcting placeholder contact information
- Removing unused fonts and JavaScript plugins
- Minifying CSS and JavaScript for production
- Optimizing product images
- Adding SEO title and meta description
- Adding Open Graph and social sharing metadata
- Adding canonical URLs
- Adding structured data for products
- Implementing a real cart / checkout backend
- Adding authentication and CMS functionality if required
- Validating HTML and removing duplicate element IDs
- Configuring contact forms securely on the server

## Git Workflow

Create a new branch for larger changes:

```bash
git checkout -b feature/update-storefront
```

Stage and commit:

```bash
git add .
git commit -m "Update storefront"
```

Push the branch:

```bash
git push -u origin feature/update-storefront
```

## License

This project is distributed under the license included in the repository's `LICENSE` file.

## Developer

**Pream Shah**

GitHub: [@preamshah](https://github.com/preamshah)

---

If you modify the project architecture, update this README so that its setup instructions and directory tree remain accurate.
