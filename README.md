# PDF_FORM_TO_DIGITAL
Leveraging OCR and Local LLM to Process Analog Handwritten text into a Digital form. 

# Requirements: 
Python 12.0
Download [Llama3] (https://ollama.com) and have it running while running the script. 

# Steps:
Open Ollama in your device

Adapt the ipynb script to your folder paths.

Create a folder with the PDF or pdfs with the handwritten text. 

Create another folder where the PDFs will be automatically converted to images. 

Run the code in the ipynb. 

# What is it doing? 

Coverts pdf to image. 

surya (https://github.com/VikParuchuri/surya) applies OCR to the images processign them as unstructured text. 
  - Note Surya provides confidence levels (There is no threshold beign used, but it could be a nice extension)

LLM structures the unstructured text into a dictionary form. 

The dataframe is up to you to export it as a csv if you wnant.
