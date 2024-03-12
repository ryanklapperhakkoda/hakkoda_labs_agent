# Hakkoda Snowflake Assistant

This is a chatbot application powered by OpenAI and built with Streamlit. It uses the GPT-3.5-turbo model to generate responses.

## Features

- Interactive chat interface
- Real-time response generation
- SQL query execution from chat responses

## Setup

1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Create a `.streamlit` folder.
4. Put your `secrets.toml` file inside the `.streamlit` folder.
5. Run the app using `streamlit run app.py`.

## Usage

Enter your query in the chat input field. The assistant will generate a response. If the response contains a SQL query, it will be executed and the results will be displayed.

## Dependencies

- OpenAI
- Streamlit
- re

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
