# PigxelMart

PigxelMart is a digital store focused on providing Minecraft-related products, including accounts, gift cards, mod packs, and server setups. This project features a modern and stylish landing page with a neon/glassmorphism design, ensuring a visually appealing user experience.

## Project Structure

```
pigxelmart
├── public
│   └── index.html          # Main HTML document for the website
├── src
│   ├── assets              # Directory for static assets (images, icons, etc.)
│   ├── components          # React components for different sections of the website
│   │   ├── Header.jsx      # Header component with logo and navigation
│   │   ├── Hero.jsx        # Hero section with welcome text and CTA
│   │   ├── ProductGrid.jsx  # Grid of product cards
│   │   ├── ProductModal.jsx # Modal for product details and purchasing
│   │   ├── AboutUs.jsx     # About us section
│   │   └── Footer.jsx      # Footer with social links and copyright
│   ├── styles
│   │   └── main.css        # Main CSS styles implementing the design
│   ├── App.jsx             # Main application component
│   └── main.jsx            # Entry point for the React application
├── package.json            # npm configuration file
└── README.md               # Project documentation
```

## Features

- **Responsive Design**: The website is fully responsive, ensuring a seamless experience on both desktop and mobile devices.
- **Neon/Glassmorphism Aesthetic**: The design incorporates modern UI trends, providing a visually striking interface.
- **Product Showcase**: A dynamic product grid displays various Minecraft-related products with detailed information.
- **User-Friendly Navigation**: Easy navigation through the header and footer sections.
- **Modal for Purchases**: A modal component allows users to view product details and make purchases without leaving the page.

## Setup Instructions

1. **Clone the Repository**:
   ```
   git clone <repository-url>
   cd pigxelmart
   ```

2. **Install Dependencies**:
   ```
   npm install
   ```

3. **Run the Application**:
   ```
   npm start
   ```

4. **Open in Browser**:
   Navigate to `http://localhost:3000` to view the application.

## Usage

- Explore the various products available in the store.
- Use the navigation menu to access different sections of the website.
- Click on product cards to view details and make purchases.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.