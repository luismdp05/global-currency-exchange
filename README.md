---

# Currency Converter

A simple and intuitive currency converter application that provides real-time exchange rates for major currencies around the world. The data is sourced from [ExchangeRate-API](https://www.exchangerate-api.com), ensuring up-to-date and reliable information.

---

## Table of Contents

- [Table of Contents](#table-of-contents)
- [🌐 About This Currency Exchange App](#-about-this-currency-exchange-app)
  - [✨ Features](#-features)
  - [🛠️ How It Works](#️-how-it-works)
  - [📊 Data Source](#-data-source)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
  - [Notes](#notes)
- [🚀 Project Structure](#-project-structure)
- [🧞 Commands](#-commands)
- [👀 Want to Learn More?](#-want-to-learn-more)

---

## 🌐 About This Currency Exchange App

This application provides real-time currency exchange rates for major currencies around the world. The data is sourced from [ExchangeRate-API](https://www.exchangerate-api.com), which provides accurate and reliable exchange rate information.

### ✨ Features
- Convert between different currencies with real-time exchange rates.
- View comprehensive exchange rate tables with your preferred base currency.
- Simple and intuitive interface for quick currency conversions.
- Support for major global currencies.

### 🛠️ How It Works
- The application fetches the latest exchange rates from a reliable API.
- Performs calculations to convert between currencies.
- Exchange rates are typically updated daily.
- Last update time is displayed with the conversion results.

### 📊 Data Source
- Powered by [ExchangeRate-API](https://www.exchangerate-api.com/).
- Provides accurate and up-to-date foreign exchange rates.
- Offers reliable currency conversion data for commercial and personal use.

---

## Installation

To set up the Currency Converter application locally, follow these steps:

1. **Clone the Repository**  
   Clone this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/your-repo/currency-converter.git
   ```

2. **Navigate to the Project Directory**  
   Move into the project folder:
   ```bash
   cd currency-converter
   ```

3. **Install Dependencies**  
   Install the required dependencies using npm:
   ```bash
   npm install
   ```

4. **Run the Development Server**  
   Start the development server to test the application locally:
   ```bash
   npm run dev
   ```

5. **Build for Production (Optional)**  
   If you want to build the application for production, run:
   ```bash
   npm run build
   ```

6. **Preview the Build (Optional)**  
   To preview the production build locally, use:
   ```bash
   npm run preview
   ```

---

## Usage

1. Open the application in your browser (usually at `http://localhost:4321` during development).
2. Enter the amount you want to convert in the **Amount** field.
3. Select the source currency in the **From** dropdown.
4. Select the target currency in the **To** dropdown.
5. Click the **Convert** button to see the converted amount.
6. The result will display the converted amount and the last updated time for the exchange rate.

Example:
```
Amount: 100
From: USD
To: EUR
Converted Amount: 95.00 EUR
Last Updated: 2023-10-01 12:00 UTC
```

---

## Contributing

We welcome contributions! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature or fix"
   ```
4. Push your changes to your fork:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request to the main repository.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

### Notes

- Ensure you have Node.js and npm installed on your system before running the installation commands.
- For API usage, make sure you have a valid API key from [ExchangeRate-API](https://www.exchangerate-api.com).

---

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

---

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

---

## 👀 Want to Learn More?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

---

Este archivo está ahora bien organizado, con una estructura clara y fácil de seguir. Si necesitas más ajustes o personalización, no dudes en decírmelo. 😊