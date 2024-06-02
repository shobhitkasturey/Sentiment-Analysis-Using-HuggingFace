# Sentiment-Analysis-Using-HuggingFace


Welcome to the Sentiment Analysis Tool, a Python application that uses the Hugging Face Transformers library to perform sentiment analysis on user-provided text. This tool leverages the `distilbert-base-uncased-emotion` model to classify text into different emotional categories.

## Features

- **Sentiment Analysis**: Analyzes the sentiment of the input text and categorizes it into predefined emotional labels.
- **User-friendly**: Simple command-line interface for easy interaction.
- **Real-time Analysis**: Provides instant feedback on the sentiment of the input text.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/sentiment-analysis-tool.git
    cd sentiment-analysis-tool
    ```

2. **Create a virtual environment**:
    ```sh
    python -m venv venv
    ```

3. **Activate the virtual environment**:
    - On Windows:
        ```sh
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source venv/bin/activate
        ```

4. **Install the required packages**:
    ```sh
    pip install -r requirements.txt
    ```

5. **Install PyTorch or TensorFlow** (if not already installed):
    - For PyTorch:
        ```sh
        pip install torch
        ```
    - For TensorFlow:
        ```sh
        pip install tensorflow
        ```

## Usage

To run the sentiment analysis tool, use the following command:

```sh
python sentiment_analysis.py
```

Once the script is running, you can enter text for sentiment analysis. Type 'exit' to quit the tool.

### Example

```
Welcome to the Sentiment Analysis Tool
Type 'exit' to quit the tool.

Enter text for sentiment analysis: I am very happy today!
Sentiment: joy

Enter text for sentiment analysis: This is the worst day of my life.
Sentiment: sadness

Enter text for sentiment analysis: exit
Exiting the tool. Goodbye!
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.



## Acknowledgements

- [Hugging Face](https://huggingface.co/) for providing the Transformers library and pre-trained models.

## Contact

For any questions or suggestions, feel free to contact me at [shobhitkasturey@gmail.com](mailto:shobhitkasturey@gmail.com).

---

Thank you for using the Sentiment Analysis Tool!
```

### Notes:
1. **Update the GitHub repository URL**: Replace `https://github.com/your-username/sentiment-analysis-tool.git` with the actual URL of your GitHub repository.
2. **License File**: If you include a `LICENSE` file in your repository, it will automatically link to the license details.
3. **Contact Information**: Replace `your-email@example.com` with your actual email address.

### Additional Steps:
1. **Create `requirements.txt`**:
    ```sh
    pip freeze > requirements.txt
    ```
    This command will generate a `requirements.txt` file with all the dependencies required for your project.

2. **Upload to GitHub**:
    ```sh
    git add .
    git commit -m "Initial commit"
    git push origin main
    ```

