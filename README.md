
# Cryptocurrency Market Data Table

A dynamic web application to display cryptocurrency market data in a user-friendly table format. The application fetches real-time data using an API and provides search and sorting functionalities.

# Features #

- **Real-Time Data**: Displays up-to-date cryptocurrency market data including image, name, symbol, current price, and total volume.
- **Search Functionality**: Allows users to search for cryptocurrencies by name or symbol.
- **Sorting Options**: Enables sorting by market capitalization and percentage change.
- **Responsive Design**: Ensures a seamless experience across different devices.
- **Interactive UI**: Clean and minimalistic design with hover effects for better user interaction.

# Demo #

[Insert a link here if the project is hosted online]

# Technologies Used #

- **HTML5**: For the basic structure of the application.
- **CSS3**: For styling and layout.
- **JavaScript (Vanilla)**: For dynamic behavior and API integration.
- **API**: Uses [CoinGecko API](https://www.coingecko.com/en/api) (or your chosen API).

# Installation #

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Navigate to the project directory:
   ```bash
   cd your-repo-name
   ```
3. Open the `index.html` file in your preferred web browser.

## Usage

1. **Search for Cryptocurrencies**:  
   - Enter the cryptocurrency name or symbol in the search bar.
   - Click the **Search** button or press `Enter` to filter the table.

2. **Sort Data**:  
   - Click the **Sort by Mkt Cap** button to sort cryptocurrencies by market capitalization.
   - Click the **Sort by Percentage Change** button to sort cryptocurrencies by 24-hour percentage change.

# File Structure #

```
project-folder/
│
├── index.html         # Main HTML file
├── style.css          # CSS file for styling
├── style.js           # JavaScript file for dynamic behavior
└── README.md          # Project documentation
```

# API Configuration #

The project fetches data from the [CoinGecko API](https://www.coingecko.com/en/api). Ensure you have access to the API and modify the `apiUrl` in `style.js` if necessary.

```javascript
const apiUrl = 'https://api.coingecko.com/api/v3/coins/markets';
const currency = 'usd';
```

# Screenshots #

### Main Interface
![Main Interface Screenshot](https://via.placeholder.com/800x400)  
_A clean and user-friendly UI for cryptocurrency market data._

# Contributing #

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

# Acknowledgments #

- [CoinGecko API](https://www.coingecko.com/en/api) for providing cryptocurrency data.
- Inspiration from modern cryptocurrency market apps.

---

Feel free to replace placeholders like `your-username`, `your-repo-name`, or screenshot links with actual project details!
