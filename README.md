# LoDJobApplication

This Jupyter Notebook app fetches a random joke and transforms it into various styles like "Dad Joke," "Knock-Knock," and "Dark Humor." Users click a button to display joke variations in a clean layout.

## Setup Instructions

1. **Install Dependencies**:

   - Install dependencies from `requirements.txt` if running locally:
     ```bash
     pip install -r requirements.txt
     ```

2. **Using Google Colab**:

   - To open this notebook in Google Colab, click the badge below:

     [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/username/my-project/blob/main/notebook.ipynb)

3. **API Key Setup**:

   - This project uses OpenAI API for generating responses.
   - **For secure access**, store your API key in a `.env` file on Google Drive and mount Google Drive in Colab as described in the notebook.
   - The `.env` file should contain:
     ```plaintext
     OPENAI_API_KEY=your_openai_api_key
     ```

4. **Run the Notebook**:
   - After mounting Google Drive, execute all cells in order.
