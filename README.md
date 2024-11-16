# Results Summary Component

This project is a web component that displays a summary of results, including individual scores and a total score. It is styled using CSS and includes responsive design for different screen sizes.

## Project Structure
results-summary-component/
├── assets/
│    images 
│       ├──icon-memory.svg
│       ├──icon-reaction.svg
│       ├──icon-verbal.svg
│       └──icon-visual.svg
├── index.html 
├── medias.css
├── README.md
└── styles.css

## Files

- **index.html**: The main HTML file that contains the structure of the results summary component.
- **styles.css**: The main CSS file that contains the styles for the component.
- **medias.css**: The CSS file that contains media queries for responsive design.
- **assets/images/**: Directory for image assets.

## Usage

1. Clone the repository.
2. Open `index.html` in a web browser to view the results summary component.

## Fonts

The project uses the Hanken Grotesk font. The font is also loaded from Google Fonts in the `index.html` file.

## CSS Variables

The project uses CSS variables for colors and gradients. These variables are defined in the `:root` selector in `styles.css`.

## Responsive Design

The project includes responsive design using media queries defined in `medias.css`. The layout adjusts for different screen sizes to ensure a good user experience on both mobile and desktop devices.

## Future Updates

For future updates I plan on having the summary scores be extracted from a JSON document instead of hard coded into the project.

## License

This project is licensed under the MIT License.