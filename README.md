# CodeSpeedUp_PythonToCPP

A tool that accelerates Python code by converting it into optimized, high-performance C++ using the open-source [Qwen model](https://huggingface.co/models). This project streamlines code optimization by automating conversion, cleanup, compilation, and execution steps.

## Features
- **Python to C++ Conversion**: Uses the Qwen model to translate Python functions into efficient C++ code.
- **Code Cleaning**: Automatically removes unwanted text, markdown formatting, and explanations.
- **Compilation and Execution**: Includes tools to compile and run the generated C++ code on x86 systems.
- **Open-Source Integration**: Built entirely with open-source frameworks such as Hugging Face Transformers and Gradio.

## Requirements
Install the required dependencies:
```bash
pip install -q python-dotenv requests gradio IPython huggingface_hub transformers bitsandbytes


Usage

    Clone the Repository:

git clone https://github.com/hamzabaccouri/CodeSpeedUp_PythonToCPP.git
cd CodeSpeedUp_PythonToCPP

Run the Notebook: Open the Python_to_CPP_Qwen_Converter.ipynb notebook in Jupyter or Colab.

Launch the Gradio App: The Gradio interface allows you to:

    Input Python code.
    Generate the corresponding optimized C++ code.
    Compile and execute the code.

    ui.launch(inbrowser=True, share=True)

File Structure

.
├── Python_to_CPP_Qwen_Converter.ipynb  # The main notebook with the full workflow
├── optimized.cpp                      # Output file containing generated C++ code
├── requirements.txt                   # Dependency list (optional)
└── README.md                          # Documentatio
