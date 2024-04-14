# Chat with PDF

This is a fun Python project that allows you to chat with a chatbot about the PDF you uploaded. and generate a PDF transcript of the conversation. The project is built using Python and Streamlit framework.

## Installation

To run this project, please follow the steps below:

Create and activate a virtual environment (optional but recommended):

```shell
python3 -m venv venv
source venv/bin/activate
```

Install the dependencies from the `requirements.txt` file:

```shell
pip install -r requirements.txt
```
Add your HUGGINGFACEHUB_API_TOKEN in `.env.example` file and rename the file to `.env`

## Running the Project

Once you have installed the required dependencies, you can run the project using Streamlit. Streamlit provides an easy way to create interactive web applications in Python.

To start the application, run the following command:

```shell
streamlit run appy.py
```

This will start the Streamlit server and open the application in your default web browser..


when virtual env is not disabled by system 
``` shell
 Set-ExecutionPolicy Unrestricted -Scope Process
 .\venv\Scripts\Activate.ps1
 ```

