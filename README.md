# llm-database-analyzer
Welcome to the Database Query Tool! This tool allows you to interact with the Atleeq Tees database using natural language queries, converting them into SQL queries and providing you with accurate answers. It's designed to make you feel like you're conversing directly with the database itself.

## Requirements

To use this tool, you'll need the following:

- A database (here we used a sample database of a company say atleeq tees which sell these 4 brands levi , nike, adidas, Van Huesen.)
- Google PALM language model, integrated using the LangChain framework.
- ChromaDB Vector Database for storing word embeddings.
- Hugging Face library for converting data into word embeddings.
- Streamlit for the user interface.

## Installation

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/yourusername/atleeq-tees-database-tool.git
   ```

2. Install the necessary dependencies:

   ```
   pip install -r requirements.txt
   ```

3. Set up your MySQL database with the required schema and populate it with data inventory.

4. Ensure you have the Google PALM language model and LangChain framework properly set up and integrated.

5. Set up ChromaDB Vector Database and ensure it's connected to the LangChain framework.

## Usage

1. Run the Streamlit UI:

   ```
   streamlit run app.py
   ```

2. Access the UI in your web browser. You'll see a text input box where you can enter your natural language query.

3. Enter your query in natural language. For example, you can ask questions like "What brands does Atleeq Tees sell?" or "How many Nike shirts are in stock?".

4. The tool will convert your query into an SQL query, fetch the relevant information from the database, and display the results to you in a human-readable format.

## Known Limitations

- Complex questions may not be answered accurately without proper evaluation.
- The system relies on pre-prepared sets of questions and corresponding SQL queries for few-shot learning. If the query is outside of these pre-prepared sets, accuracy may be compromised.

## Contributing

Contributions to improve the tool are welcome! If you encounter any issues or have suggestions for enhancements, feel free to open an issue or submit a pull request on GitHub.


## Acknowledgments

- Thanks to the developers of Google PALM, LangChain, Hugging Face, ChromaDB, and Streamlit for their fantastic tools and frameworks.
