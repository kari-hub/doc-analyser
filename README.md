# Doc-analyser

Doc Analyser is a tool designed to analyze and generate summaries of documents in PDF formats. It uses Chainlit, running on Ollama and Llama3 to provide efficient and accurate document summarisation.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Analyze and summarize PDF documents
- Utilizes Chainlit for robust analysis
- Runs on Ollama and Llama3 for powerful processing
- Easy-to-use command-line interface

## Installation

### Prerequisites

- Python 3.8 or higher
- Pip (Python package installer)
- Preinstalled Ollama on desktop

### Steps

1. **Clone the repository**:

   ```sh
   git clone https://github.com/kari-hub/doc-analyser.git
   cd doc-analyser
   ```

2. **Create a virtual environment** (optional but recommended):

   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages**:

   ```sh
   pip install -r requirements.txt
   ```

4. **Install additional dependencies for Ollama and Llama3**:
   - Follow the instructions for [Ollama](https://ollama.ai/documentation) and [Llama3](https://llama.ai/documentation) to ensure all necessary dependencies and environment setups are complete.

## Usage

1. **Run the Document Analyser**:

   ```sh
   python main.py /path/to/your/document.pdf
   ```

2. **View the generated summary**:
   The summary will be output to the terminal or saved to a specified file, depending on your configuration.

## Contributing

We welcome contributions to enhance the Doc Analyser. To contribute:

1. Fork the repository.
2. Create a new branch:

   ```sh
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit them:

   ```sh
   git commit -m "Add your feature"
   ```

4. Push to the branch:

   ```sh
   git push origin feature/your-feature-name
   ```

5. Open a pull request detailing your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Chainlit](https://chainlit.io/)
- [Ollama](https://ollama.ai/)
- [Llama3](https://llama.ai/)
