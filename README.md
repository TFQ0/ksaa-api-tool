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


## CORS Extension Required

You need to install a browser extension to allow cross-origin requests when testing the API from a local HTML file.

**📥 Install CORS Extension:**

1. **Download the Extension:**
   - Visit: https://mybrowseraddon.com/access-control-allow-origin.html

2. **Configure the Extension:**
   - After installation, click the extension icon in your browser toolbar
   - **Enable** the "Access-Control-Allow-Origin" toggle
   - The extension icon should show as "ON" or active

3. **Important Security Note:** ⚠️
   - **Only enable this extension when testing APIs**
   - **Disable it when browsing other websites** for security
   - This extension bypasses important browser security features


## Getting Started

1. **Install CORS Extension** (see Prerequisites above)

2. Open `KsaaFalakApi1.html` in your web browser.

3. **Enable CORS Extension** before testing

4. Enter your API key in the configuration section.

5. Select an endpoint and start exploring the API!

## Usage

1. **Configure API Key**
   - Enter your API key in the configuration section
   - The key will be saved in your browser's local storage

2. **Select Endpoint**
   - Click on any endpoint card to view its parameters
   - Each endpoint displays its HTTP method and description

3. **Fill Parameters**
   - Complete required parameters (marked with *)
   - Optional parameters can be left empty
   
4. **Execute Request**
   - Click "Execute Request" to call the API
   - Use Ctrl/Cmd + Enter as a keyboard shortcut

5. **View Results**
   - Switch between Table and Raw JSON views
   - Use filters and sorting in table view
   - Export data if needed

## Troubleshooting

**Common Issues:**

- **CORS Error:** Make sure the CORS extension is installed and enabled
- **401 Unauthorized:** Check that your API key is correct
- **Network Error:** Verify the API base URL is correct
- **No Data:** Some endpoints may return empty results based on parameters

**Browser Console:**
- Press F12 to open developer tools
- Check the Console tab for detailed error messages
