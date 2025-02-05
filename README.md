# End-to-End GENAI App Using DeepSeek R1 Model

## Project Description
This project demonstrates an end-to-end generative AI application using the **DeepSeek R1** model. The app utilizes **Ollama** to run the model locally, **Langchain** for chaining and processing the model's responses, and **Streamlit** for creating an interactive web interface.

## Technologies Used
- **DeepSeek R1 Model** (Deepseek R1-1.5B)
- **Ollama**: Used to run the DeepSeek model locally
- **Langchain**: To manage and chain the language model prompts
- **Streamlit**: To create an interactive user interface
- **Python 3.10**

## Installation Instructions
Before using this repo, ensure that **Ollama** is already installed on your system. Here are the installation steps for the repo:

1. **Install Ollama**:
   - You need to install **Ollama** and download the respective model (in this case, **Deepseek R1-1.5B**). Follow the instructions on the Ollama website to get set up: [Ollama Installation](https://ollama.com).

2. **Create Virtual Environment**:
   - Once Ollama and the model are installed, you can create a virtual environment and activate it in the terminal.
     ```bash
     conda create -n my_env python=3.10
     conda activate my_env
     ```

   
4. **Install Dependencies**:
   - In the virtual environment, you can install the necessary Python libraries using the following command:
     ```bash
     pip install -r requirements.txt
     ```

5. **Run the App**:
   - After installation, start the application by running the following command:
     ```bash
     streamlit run app.py
     ```
   - This will launch the application on your local server.

## Code Explanation
This project consists of several components:
- **`app.py`**: The main file that uses Streamlit to create a user interface where you can interact with the DeepSeek model.
- **`requirements.txt`**: A file listing all the necessary libraries needed to run the app.
- **Ollama Integration**: The DeepSeek R1-1.5B model is loaded and processed using Ollama.
- **Langchain**: Manages the model's input-output chains to enhance user interaction.

## Features
- Run **DeepSeek R1-1.5B** model locally.
- Use **Streamlit** to build a simple web app.
- Seamless integration of **Langchain** for better chaining and processing of responses from the model.

## Acknowledgements
This project was inspired by a tutorial on YouTube that helped in understanding the integration of Ollama and Streamlit. 

## Contributing
Feel free to fork this project, open issues, or submit pull requests. Contributions are welcome!


