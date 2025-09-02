### 🔄 Python to Other Language Converter

This project provides a simple, web-based tool for converting Python code into other programming languages using powerful Large Language Models (LLMs). The interface, built with Gradio, allows you to easily translate code from your browser.

-----

### Features

  * **Multilingual Conversion**: Converts Python code to C, C++, Java, or JavaScript.
  * **LLM Selection**: Choose between **OpenAI's GPT-4o-mini** and **Ollama's Llama 3.2**.
  * **Mac M4 Optimization**: The assistant is specifically prompted to generate code for the Mac M4 architecture.

-----

### Use Cases

  * **Learning New Languages**: Quickly see how Python code translates to other languages.
  * **Platform Migration**: Get a head start on migrating a Python application to a new language.
  * **Rapid Prototyping**: Generate code snippets in multiple languages for testing.

-----

### Requirements

To run this application, you need to install the following Python libraries:

```bash
pip install gradio==4.36.1 ollama==0.2.0 openai==1.35.13 python-dotenv==1.0.1
```

-----

### Setup and Usage

1.  **Clone the Repository**.
2.  **Set Up API Key**: Create a `.env` file and add your OpenAI API key: `OPENAI_API_KEY='your-api-key-here'`.
3.  **Run the Notebook**: Open and run the `app.ipynb` Jupyter Notebook.
4.  **Translate Code**: Access the Gradio interface via the provided URL, paste your Python code, select a language and LLM, and get your converted code.
