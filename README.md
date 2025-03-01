# Financial Team Agents using Gemini API and Phi

This repository contains a Python script that utilizes the [Phi](https://github.com/hwchase17/phi) framework to create AI agents for web search and financial data retrieval. The agents leverage Google's Gemini model and various tools for enhanced functionality.

## Features
- **Web Agent**: Uses DuckDuckGo search to retrieve relevant information with sources.
- **Finance Agent**: Fetches financial data, including stock prices, analyst recommendations, and company information using Yahoo Finance.
- **Agent Team**: Combines the Web and Finance agents to provide structured insights.
- **Streaming Response**: Generates real-time outputs for user queries.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/phi-agents.git
   cd phi-agents
   ```

3. Create a python environmet:
   ```sh
   python -m venv ai_agent
   ```
4. Activate the env:
   ```sh
   ai_agent\Scripts\activate
   ```
4. Install dependencies:
   ```sh
   pip install phidata duckduckgo-search yfinance google-generativeai dotenv
   ```

5. Set up environment variables by creating a `.env` file:
   ```
   API_KEY=your_api_key_here
   ```

## Usage

Run the script to execute an example query for NVDA stock:
```sh
python script.py
```

```

## Contributing
Feel free to fork this repository and submit pull requests for improvements.

## License
This project is licensed under the MIT License.


