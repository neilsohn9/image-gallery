# Image Gallery Project

## Overview
This is a simple, responsive image gallery built using HTML, CSS, and JavaScript. The gallery displays a grid of images that users can click to view in a modal (enlarged view). The modal includes navigation buttons to cycle through images and supports keyboard navigation for accessibility.

## Features
- **Responsive Grid Layout**: Images are displayed in a grid that adapts to different screen sizes.
- **Modal View**: Clicking an image opens it in a modal with a darkened background.
- **Navigation**: Users can navigate through images using "Previous" and "Next" buttons or arrow keys.
- **Keyboard Support**: Use `Arrow Left`, `Arrow Right`, and `Escape` keys for navigation and closing the modal.
- **Hover Effects**: Images scale slightly on hover for a better user experience.
- **Close Modal**: Click the close button (`×`), click outside the image, or press `Escape` to close the modal.

## Project Structure

image-gallery/

├── images/
│   ├── image1.jpg
│   ├── image2.jpg
│   ├── image3.jpg
│   └── (add more images as needed)
├── index.html
├── styles.css
├── script.js
└── README.md


## Setup Instructions
1. **Clone or Download**:
   - Clone this repository or download the project files.
2. **Add Images**:
   - Place your images in the `images/` folder.
   - Update the `index.html` file to include your images by adding `<img>` tags with the correct file paths and alt text.
3. **Open the Project**:
   - Open `index.html` in a web browser to view the gallery.
   - Alternatively, use a local development server (e.g., via VS Code's Live Server extension or `python -m http.server`).
4. **Customize**:
   - Modify `styles.css` to change the gallery's appearance (e.g., grid size, colors, or modal styles).
   - Adjust `script.js` to add new functionality (e.g., image captions or additional navigation options).

## Usage
- Click on any image in the grid to open it in the modal.
- Use the "Previous" (`<`) and "Next" (`>`) buttons or arrow keys to navigate through images.
- Click the close button (`×`), press `Escape`, or click outside the image to close theOverall, the modal.

## Dependencies
- None. This project uses vanilla HTML, CSS, and JavaScript.

## Browser Compatibility
- Works on modern browsers (Chrome, Firefox, Safari, Edge).
- Responsive design ensures compatibility with mobile and desktop devices.

## Notes
- Ensure all image files in the `images/` folder are correctly referenced in `index.html`.
- For better performance, consider compressing images to reduce file size.
- Add alt text to all images for accessibility.

## License
This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).

## Contributing
Feel free to submit issues or pull requests to improve the project. Suggestions for new features or bug fixes are welcome!
