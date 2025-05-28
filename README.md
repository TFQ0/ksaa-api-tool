# KSAA API Explorer

A modern, interactive web interface for exploring and testing the Falak API endpoints. This tool provides a user-friendly way to interact with KSAA's API services, featuring real-time data visualization and testing capabilities.

![KSAA API Explorer](screenshot.png) *(Add your screenshot here)*

## Features

- 🚀 Interactive API endpoint exploration
- 📊 Real-time data visualization with table and JSON views
- 🔑 API key management with local storage
- 📝 Dynamic parameter handling
- 📋 Beautiful tabular data display using Tabulator
- 🎨 Modern, responsive UI design
- ⚡ Fast and efficient API testing

## Available Endpoints

The explorer provides access to the following Falak API endpoints:

- **Statistics** (`GET /v1/external/statistics/{corpusId}`)
  - Get corpus statistics by ID
  
- **N-grams** (`GET /v1/external/ngrams`)
  - Search for n-grams in the corpus
  
- **Concordance** (`GET /v1/external/concordance`)
  - Search concordance lines
  
- **Collocations** (`GET /v1/external/collocations`)
  - Find word collocations
  
- **Frequency** (`GET /v1/external/frequency`)
  - Get word frequency data
  
- **Corpora** (`GET /v1/external/corpora`)
  - List all available corpora

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ksaa-api-explorer.git
   ```

2. Open `index.html` in your web browser.

3. Enter your API key in the configuration section.

4. Select an endpoint and start exploring the API!

## Usage

1. **Configure API Key**
   - Enter your API key in the configuration section
   - The key will be saved in your browser's local storage

2. **Select Endpoint**
   - Click on any endpoint card to view its parameters
   - Each endpoint displays its HTTP method and description

3. **Set Parameters**
   - Fill in the required parameters (marked with *)
   - Optional parameters can be left empty

4. **Execute Request**
   - Click the "Execute Request" button or press Ctrl/Cmd + Enter
   - View results in either table or JSON format

5. **View Results**
   - Switch between Table and Raw JSON views
   - Filter and sort data in the table view
   - Copy raw JSON data for further use

## Keyboard Shortcuts

- `Ctrl/Cmd + Enter`: Execute request
- `Escape`: Reset parameters

## Dependencies

- [Tabulator](https://tabulator.info/) v5.5.2 - For interactive table display

## Browser Support

The API Explorer is compatible with all modern browsers:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built for the King Salman Academy for Arabic Language
- Uses the Falak API services
- Tabulator library for data visualization

## Support

For support or questions about the API Explorer, please [open an issue](https://github.com/yourusername/ksaa-api-explorer/issues) on GitHub.

---

Made with ❤️ for the Arabic language community 