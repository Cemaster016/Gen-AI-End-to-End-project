# Gen-AI-End-to-End-project: Text Generation with OpenAI and Hugging Face
## Overview
This mini project demonstrates the end-to-end process of text generation using Generative AI (Gen-AI) models from OpenAI and Hugging Face. The goal is to showcase how these models can be used to generate creative and coherent text.

## Tools and Libraries Used
- OpenAI GPT-3 model via the OpenAI API
- Hugging Face Transformers library for model integration
- Python for coding and script execution
- Flask for creating a simple web interface

## Project Structure
- `main.py`: Python script for integrating the OpenAI and Hugging Face models
- `templates/`: Directory containing HTML templates for the web interface
- `static/`: Directory for storing static files such as CSS and JavaScript
- `requirements.txt`: File listing the required Python libraries and dependencies

## Usage
1. Clone the repository: git clone https://github.com/Cemaster016/Gen-AI-End-to-End-project.git
2. Install the required libraries: pip install -r requirements.txt
3. Get your OpenAI API key and set it as an environment variable: export OPENAI_API_KEY='your-api-key
4. Run the Flask app: python main.py
5. Access the web interface in your browser at http://localhost:5000

## Example
Once the app is running, you can enter a prompt (e.g., "Once upon a time") into the text box and click the "Generate" button. The app will use the OpenAI and Hugging Face models to generate a continuation of the prompt, displaying the result on the web interface.

## Future Improvements
- Implement user authentication for API access
- Add more customization options for text generation
- Improve the user interface for better usability

## Credits
- OpenAI for providing the GPT-3 model and API
- Hugging Face for the Transformers library and model integration

---
