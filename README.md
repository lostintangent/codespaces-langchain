# 🦜🔗 Codespaces LangChain Template

This template provides a one-click dev environment for building "LLM apps" with [LangChain](https://github.com/hwchase17/langchain), Codespaces, and GPT-3. With it, you'll get [free access](https://github.blog/changelog/2022-11-09-codespaces-for-free-and-pro-accounts/) to a VS Code-based web editor, complete with a fully-configured Python playground, that includes the neccessary SDKs, libraries, and IDE extensions 🐱‍💻

<img width="700px" src="https://user-images.githubusercontent.com/116461/214455181-bee24f04-3ad1-4269-ad1f-3428a3e860ea.png" />

## Getting Started

1. Create a repo from this template, by clicking the green `Use this template` button, and selecting `Create a new repository`. Name the repo whatever you'd like 👍

    <img width="150px" src="https://user-images.githubusercontent.com/116461/214456882-1821146a-5d10-4571-b55f-69254800776f.png" />

1. In order to interact with GPT-3, you'll need to create an account with [OpenAI](https://openai.com/api/), and generate an API key that LangChain can use. Once you have that, create a new [Codespaces repo secret](https://docs.github.com/en/codespaces/managing-codespaces-for-your-organization/managing-encrypted-secrets-for-your-repository-and-organization-for-github-codespaces#adding-secrets-for-a-repository) named `OPENAI_API_KEY`, and set it to the value of your API key.

1. Open your new repo in a Codespace by clicking the green `Code` button on the repo's homepage, and selecting `Create codespace on main`

    <img width="300px" src="https://user-images.githubusercontent.com/116461/214457831-28778e80-d314-4c7c-a199-948d5d9828e9.png" />

1. Once you're within the web editor, simply open any of the notebooks within the `/examples` folder, and select `Run All` in the notebook's toolbar. From there, you can change any of the prompts and/or code, and then re-run the cell/notebook, in order to get a better intuition for how LangChain can help you build your own custom chains 🚀

> Optionally, if you'd like to explore the sample that automates Google search qierues, create an account with [SerpAPI](https://serpapi.com/), generate an API key, and set it as a Codespaces secret called `SERPAPI_API_KEY`.
