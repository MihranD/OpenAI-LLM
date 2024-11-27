# Building a Practical LLM-Powered Solution with OpenAI
***
An OpenAI-powered LLM model that scrapes web pages based on user and system prompts.

***
The project integrates essential libraries, such as openai, requests, and BeautifulSoup, to interact with the OpenAI API, manage web scraping, and process data effectively. These tools enable seamless content extraction and summarization for practical applications.

![Web Scraping](https://github.com/MihranD/OpenAI-LLM/blob/main/images/web-scraping.png)

## Project Organization
----------------------------------------------------------------------------------------------
    ├── .gitignore          <- Includes files and folders that we don't want to control
    |
    ├── images              <- Images for use in this project
    │   └── web-scraping.png   <- Web scraping image
    |
    ├── main.ipynb          <- Main jupyter file that needs to be run
    |
    ├── requirements.txt    <- The required libraries to deploy this project. 
    |                       Generated with `pip freeze > requirements.txt`
    └── README.md           <- The top-level README for developers using this project.

## Project Introduction

### Business Problem

Our goal is to design a tool that acts like a smart web browser:
you provide it with a URL, and it summarizes the content for you in a concise and clear way—a true Reader's Digest for the Internet!

### Problem Definition

The overwhelming volume of information on the web makes extracting relevant insights time-consuming and inefficient. This project leverages OpenAI's language model to create a tool that automatically summarizes web page content, simplifying information consumption and enhancing productivity.

### Model Output Example

`display_summary("https://netflix.com")`

![Neflix Web Scraping](https://github.com/MihranD/OpenAI-LLM/blob/main/images/example-netflix.png)

## Conclusion

Here we explored how to interact with the Cloud API of a leading AI model like OpenAI's Frontier Model. We specifically applied the power of AI to Summarization — a fundamental use case in Generative AI. Summarization has countless business applications, such as:
* Summarizing news articles for quick updates.
* Condensing financial performance reports for stakeholders.
* Crafting concise resumes or cover letters from extensive details.

The possibilities are endless.

## How to run the app

Follow these steps to set up and run the application:

1. **Create a `.env` file**  
   Add your OpenAI API key to the `.env` file in the following format:  
   ```plaintext
   OPENAI_API_KEY=sk-proj-blabla
   ```

2. **Install Dependencies**  
   Run the following command to install all required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

3. **Open and Run the Notebook**  
   Open the `main.ipynb` file in Jupyter Notebook and execute the cells to run the application.
