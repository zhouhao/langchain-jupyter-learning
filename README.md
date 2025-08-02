# Jupyter Deno LangChain Learning

This project demonstrates how to use [LangChain](https://js.langchain.com/docs/) with Deno in a Jupyter notebook environment. It shows how to load environment variables, interact with OpenAI's API, and use LangChain's chat models.


## What is LangChain?

[LangChain](https://js.langchain.com/docs/) is a framework for developing applications powered by language models. It provides tools for prompt management, chaining, memory, and integrations with various LLM providers like OpenAI.

## Example Usage

The notebook demonstrates:

- Loading environment variables using Deno's standard library.
- Creating a chat model with LangChain's `ChatOpenAI`.
- Sending a prompt and receiving a response from OpenAI.



## Setup

1. Add your OpenAI API key to the `.env` file:

    ```
    OPENAI_API_KEY=your-openai-api-key
    ```

2. Open [`deno.ipynb`](deno.ipynb) in a Jupyter environment with Deno kernel support.

3. Run the notebook cells to interact with the LangChain chat model.

## Requirements

- [Deno](https://deno.com/)
- [Jupyter](https://jupyter.org/) with Deno kernel

