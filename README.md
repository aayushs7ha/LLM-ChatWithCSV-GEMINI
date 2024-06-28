## Gemini for CSV
### Gemini for CSV is a Streamlit application that allows users to interact with their CSV data using natural language queries. The app leverages the Gemini Flash model to generate pandas commands and provide natural language responses based on user queries. It supports various data analysis operations and plotting commands.

## Features
- Upload CSV files and explore data
- Generate pandas commands based on natural language queries
- Perform data analysis and visualization using generated commands
- Interactive chat interface for seamless user experience
-Installation

### Clone the repository:


``` bash
git clone https://github.com/your-username/gemini-for-csv.git
```
```
> cd gemini-for-csv
```

## Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

# Install the required dependencies:

```bash
pip install -r requirements.txt
```

#### Set up environment variables:

- Create a .env file in the root directory of the project.
- Add your Gemini Flash API key to the .env file:

```
API_KEY="your_gemini_flash_api_key"
```

## Usage
## Run the Streamlit app:

```bash
streamlit run gemini.py

```
## Open your web browser and navigate to http://localhost:8501.

- Upload a CSV file using the file uploader.

- Interact with your data by typing natural language queries in the chat input.

### Example Queries
- "Show me the average of column A."
- "Plot a histogram of column B."
- "Group the data by column C and show the sum of column D."
