# CodeScriber: Code Documentation Generator

## Project Overview
Python-based machine learning pipeline using Hugging Face’s Transformers library to generate documentation from code, leveraging the T5 model architecture for sequence-to-sequence learning; utilized GitHub Actions to automate training

## Getting Started

### 1. Clone Repository
```bash
git clone https://github.com/dkaty123/CodeDocAI
cd nlp_code_doc
```

### 2. Install Dependencies
Run the command below to install all the dependencies needed:
```bash
pip install -r dependencies.txt
```

### 3. Run the Streamlit App
Once the model is trained, run the app:
```bash
streamlit run interface/website.py
```

### 4. Access App
Once the app is running, open the URL provided by Streamlit 
```bash 
http://localhost:8501
```

## Usage
1. Paste a code snippet into the text area in the Streamlit interface.
2. Click "Generate Documentation" to generate the documentation for your code.

### Example Code Snippet
```bash
def multiply(a, b):
    #This function returns the product of variables a and b
    return a * b
```

## Future Improvements
1. Only works if you provide one function at a time with detailed comments
2. Integrate the Tranformers and BART Models to summarize the documentation
3. Handle different training dataset types (i.e .json, csv etc..)
4. Being able to download the generated documentation
