# Falak API Endpoints

A interface for testing the Falak API endpoints. This page provides a user-friendly way to interact with KSAA's API services.

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

- **custom-search** (`/v1/external/custom-search/`)  
  - Stem search Api


## Getting Started

1. Open `KsaaFalakApi1.html` in your web browser.

2. Enter your API key in the configuration section.

3. Select an endpoint and start exploring the API!

## Usage

1. **Configure API Key**
   - Enter your API key in the configuration section
   - The key will be saved in your browser's local storage

2. **Select Endpoint**
   - Click on any endpoint card to view its parameters
   - Each endpoint displays its HTTP method and description

3. **View Results**
   - Switch between Table and Raw JSON views
