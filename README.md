# 🦜🔗 Codespaces LangChain Template

This template provides a one-click dev environment for building "LLM apps" with [LangChain](https://github.com/hwchase17/langchain), Codespaces, and GPT-3. To get started, simply click the `Use this template` button, and then select `Open in a Codespace`.

After a few seconds, you'll be dropped into a VS Code-based web editor, complete with a fully-configured Python environment which includes the neccessary SDKs, libraries, and editor extensions 🐱‍💻

## Pre-requisites

In order to interact with GPT-3, you'll need to create an account with [OpenAI](https://openai.com/api/), and generate an API key that LangChain can use. Once you have that, create a new [Codespaces user secret](https://github.com/settings/codespaces/), named `OPENAI_API_KEY`, and set it to the value of your API key.

> Optionally, if you'd like to explore the sample that automates Google search qierues, create an account with [SerpAPI](https://serpapi.com/), generate an API key, and set it as a Codespaces secret called `SERPAPI_API_KEY`.

## Getting Started

Once you set your API key and are in the Codespace, simply open any of the notebooks within the `/examples` folder and run the cells to learn about the respective APIs/scenarios. Feel free to change/add to the code in order to get a better intuition for how to use LangChain to build your own custom chains 🚀