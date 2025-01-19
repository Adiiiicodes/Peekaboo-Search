# README: AdVance

## Project Overview
AdVance is an AI-powered research and competitor analysis tool designed to streamline advertisement creation. By leveraging cutting-edge APIs and analytics, AdVance provides actionable insights to craft campaigns that outperform the competition. Whether you're analyzing trends, understanding consumer sentiment, or evaluating competitor strategies, AdVance simplifies the process with intuitive features and powerful integrations.

---

## Key Features

1. **Comprehensive Search**: Perform detailed searches for competitor ads, trends, and product insights.
2. **AI-Powered Summarization**: Generate concise summaries from web results to save time.
3. **Visual Insights**: Trend graphs, sentiment analysis, and market share charts.
4. **Competitor Analysis**: Evaluate strengths, weaknesses, and opportunities in competitor ads.
5. **Image and Text Search**: Integrates Google Custom Search API for text and image results.

---

## Installation and Setup

### Prerequisites
- A modern web browser (e.g., Chrome, Firefox).
- Node.js (optional, for managing dependencies).
- Internet connection for API access.

### Steps

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd AdVance
   ```
3. **Configure API Keys**:
   Edit `Config/config.js` with your API credentials:
   ```javascript
   const CONFIG = {
       GOOGLE_API_KEY: '<your-google-api-key>',
       GOOGLE_SEARCH_ENGINE_ID: '<your-search-engine-id>',
       GROQ_API_KEY: '<your-groq-api-key>'
   };
   ```
4. **Run the Application**:
   Open `index.html` in your browser to start using the tool.

---

## Directory Structure
```
AdVance/
├── README.md
├── d.js
├── index.html
├── script.js
├── style.css
├── Config/
│   └── config.js
├── Documentation/
│   └── Documentation.md
└── images/
```

- **index.html**: The core HTML file for the application.
- **script.js**: Main JavaScript file for handling API calls and UI interactions.
- **style.css**: Contains all styling for the application.
- **Config/config.js**: Stores configuration values like API keys.
- **Documentation/Documentation.md**: Detailed technical documentation.
- **images/**: Folder for storing assets used in the UI.

---

## How to Use

1. Open `index.html` in your browser.
2. Enter a query in the search bar (e.g., "AI in advertising").
3. Choose desired features:
   - **Search Results**: Get web and image results for competitor ads.
   - **Summarization**: Receive concise insights from search data.
   - **Graphs & Analysis**: Visualize trends, sentiment, and market shares.
4. View results, summaries, and actionable insights to refine your ad strategy.

---

## APIs Used

1. **Google Custom Search API**
   - For retrieving text and image results from the web.

2. **Groq API**
   - AI-powered summarization and competitor analysis.

3. **Chart.js**
   - For generating visual insights and trend graphs.

---

## Troubleshooting

- **API Errors**:
  - Check API key configurations in `Config/config.js`.
  - Ensure API limits are not exceeded.

- **No Internet Connection**:
  - Verify your network connection.

- **UI Issues**:
  - Clear browser cache or try another browser.

---

## Future Enhancements

1. Enhanced security with server-side API key management.
2. Advanced filtering options for detailed searches.
3. Improved mobile responsiveness.
4. User account integration for saving queries and results.

---

## License
This project is licensed under the MIT License. See `LICENSE` for details.

---

## Contributing
Contributions are welcome! If you'd like to improve the project:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## Contact
For queries or feedback, please reach out to [support@advanceapp.com](mailto:support@advanceapp.com).

