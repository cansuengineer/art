# Cansu Sarp Art Catalog

This project is a simple and responsive art gallery webpage built using [Bootstrap](https://getbootstrap.com/). It showcases a collection of artworks in a clean, grid-based layout and is designed to work well on both desktop and mobile devices.


<img width="2880" height="2486" alt="Cansu Sarp Art Catalog" src="https://github.com/user-attachments/assets/75c9cd96-004e-4f24-846d-8f42e81a3fe9" />



## Features

- **Responsive Design:** Uses Bootstrap's grid system to ensure the gallery looks great on all screen sizes.
- **Image Gallery:** Displays a selection of artwork images organized in three columns.
- **Custom Styling:** Includes additional styles in [`src/css/styles.css`](src/css/styles.css) for improved appearance.
- **Easy Customization:** You can easily add, remove, or update images and styles.

## Project Structure

```
art_catalog/
├── src/
│   ├── index.html        # Main HTML file for the gallery
│   ├── css/
│   │   └── styles.css    # Custom CSS styles
│   ├── js/
│   │   └── main.js       # JavaScript file (currently empty)
│   └── images/           # Artwork images
│       ├── lion.png
│       ├── rhino.png
│       ├── balik1.png
│       ├── Balik6.png
│       ├── cat.png
│       ├── cat2.png
│       ├── fil.png
│       ├── jaguar.png
│       └── kalamar.png
├── package.json          # Project configuration and dependencies
└── README.md             # Project documentation
```

## Getting Started

To run this project locally:

1. **Clone the repository:**
   ```sh
   git clone <repository-url>
   cd art_catalog
   ```

2. **Install dependencies:**
   Make sure you have [Node.js](https://nodejs.org/) and npm installed. Then run:
   ```sh
   npm install
   ```

3. **Start the development server:**
   ```sh
   npm start
   ```
   This will launch the site using `live-server`. Alternatively, you can open [`src/index.html`](src/index.html) directly in your browser.

## Customization

- **Images:** Add or replace images in the [`src/images/`](src/images/) folder. Update [`src/index.html`](src/index.html) to display new images.
- **Styles:** Edit [`src/css/styles.css`](src/css/styles.css) to change colors, fonts, spacing, and other visual elements.
- **JavaScript:** Add interactive features by editing [`src/js/main.js`](src/js/main.js).

## License

This project is licensed under the MIT License.

---

**Author:** Cansu Sarp
