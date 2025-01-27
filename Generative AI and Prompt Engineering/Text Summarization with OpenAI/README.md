# Text Summarization with OpenAI's GPT-3.5 Turbo

This project demonstrates how to summarize text using OpenAI's GPT-3.5 Turbo model via the OpenAI Python library. It utilizes the Chat Completion feature to process text input and generate a concise summary.

## Getting Started

These instructions will get you up and running with the project on your local machine for development and testing purposes.

### Prerequisites

- Python 3.6+
- An OpenAI API key

## Retrieving OpenAI API Key


1. **Sign Up/Login to OpenAI**:
   - If you don't already have an account, visit the OpenAI website at [openai.com](https://openai.com) and sign up for an account. If you have an account, log in using your credentials.

2. **Navigate to API Section**:
   - Once logged in, navigate to the API section of the OpenAI website. You can usually find this in the main menu or dashboard.

3. **Request API Access**:
   - Look for the option to request API access or generate an API key. Click on it to proceed.

4. **Provide Necessary Information**:
   - Fill out any required forms or fields with accurate information. This may include details about your intended use case or project.

5. **Receive API Key**:
   - Once your request is approved, you'll receive your API key. This key is typically provided in the form of a string of alphanumeric characters.

6. **Secure Your API Key**:
   - Keep your API key secure and avoid sharing it publicly. Treat it like a password and store it securely. Avoid hardcoding it directly into your code.

7. **Start Using the API**:
   - You can now use your OpenAI API key to access the available APIs and integrate them into your applications. Refer to the OpenAI documentation for guidance on how to use the API effectively.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/b8234/Azure-AI-Projects.git
   cd Azure-AI-Projects/Generative\ AI\ and\ Prompt\ Engineering/Text\ Summarization\ with\ OpenAI
   ```

2. **Install the required Python packages:**

   ```bash
   pip3 install openai python-dotenv
   ```

   Or install the required dependencies via requirements, run the following command:

   ```bash
   pip3 install -r requirements.txt
   ```

3. **Set up your environment variables:**

   Create a `.env` file in the root directory of the project and add your OpenAI API key:

   ```
   OPENAI_API_KEY='your_openai_api_key_here'
   ```

### Usage

1. **Prepare Your Text File:**

   Create a text file named [`sample-text.txt`](https://github.com/b8234/Azure-AI-Projects/blob/main/Generative%20AI%20and%20Prompt%20Engineering/Text%20Summarization%20with%20OpenAI/sample-text.txt) in the root directory and insert the text you wish to summarize.

2. **Run the Script:**

   Execute the script to generate the summary:

   ```bash
   python3 gpt_summarizer.py
   ```

   Replace [`gpt_summarizer.py`](https://github.com/b8234/Azure-AI-Projects/blob/main/Generative%20AI%20and%20Prompt%20Engineering/Text%20Summarization%20with%20OpenAI/gpt_summarizer.py) with the path to the Python script provided above if you've named it differently or stored it in a specific directory.

### Example

Given a text file `sample-text.txt` with the content you need summarized, running the script will print the summarized text to the console.

### Handling Errors

The script includes basic error handling for common issues such as missing API keys or file not found errors. Ensure your `.env` file is correctly configured and that the text file exists in the specified path.

## Migrating to the Latest Version

If you're using the OpenAI Python library, it's essential to keep your code up-to-date with the latest changes and improvements. You can migrate your code to the latest version by following the instructions provided in the [OpenAI Python repository discussions](https://github.com/openai/openai-python/discussions/742) or by using the [Grit.io migrations tool](https://app.grit.io/migrations/new/openai).


## Acknowledgments

- OpenAI team for providing the API and Python library.
- Contributors and maintainers of the `python-dotenv` package.

## Contributing

Your contributions are welcome! If you have suggestions for improving the script or have found a bug, please open an issue or a pull request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

If you have any questions or feedback, feel free to [open an issue](https://github.com/b8234/Azure-AI-Projects/issues/new). I welcome your input and suggestions to improve this repository further.
