# Airport Simulator: Plane Tycoon Website

A modern, mobile-first website for the Airport Simulator: Plane Tycoon game. This website features a responsive design, dynamic content loading from JSON, and an embedded game iframe.

## Features

- Mobile-first responsive design
- Modern cartoonish style
- Dynamic content loading from JSON
- Smooth scrolling navigation
- Embedded game iframe
- System fonts for optimal performance
- Flexbox layout system

## Project Structure

```
.
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── data/
│   └── content.json
├── images/
│   └── (place your images here)
└── index.html
```

## Setup Instructions

1. Clone this repository
2. Add your images to the `images/` directory
3. Update the content in `data/content.json` if needed
4. Serve the files using a local web server

### Running a Local Server

You can use any of these methods to run a local server:

Using Python 3:

```bash
python -m http.server 8000
```

Using Node.js:

```bash
npx http-server
```

Then visit `http://localhost:8000` in your browser.

## Customization

### Modifying Content

All website content is stored in `data/content.json`. You can modify the text and image paths there.

### Styling

The website uses CSS variables for easy theme customization. Main variables are defined in the `:root` selector in `styles.css`.

### Adding New Sections

1. Add the section content to `content.json`
2. Create the HTML structure in `index.html`
3. Add the corresponding styles in `styles.css`
4. Update the JavaScript in `main.js` to load the new content

## Browser Support

The website supports all modern browsers including:

- Chrome
- Firefox
- Safari
- Edge

## Notes

- The game iframe requires an active internet connection
- For optimal performance, compress your images before adding them to the `images/` directory
- The website uses system fonts for better performance and consistent look across platforms
