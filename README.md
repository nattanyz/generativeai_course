# Description
Here is the github repository for the files which I used to teach my courses in Institute of Systems Science, National University of Singapore

## Jupyter Notebooks Overview

### prompt_engineering/prompt_engineering_day1_solution.ipynb
A comprehensive introduction to prompt engineering for large language models (LLMs) such as OpenAI's GPT-4 and Anthropic's Claude. Covers principles of prompt design, API usage, message formatting, model parameters (max_tokens, temperature, stop sequences), and system prompts. Includes hands-on code examples for both OpenAI and Anthropic APIs.

### prompt_engineering/understanding_anthropic_models.ipynb
Demonstrates how to retrieve and display a list of available models from the Anthropic AI platform using their Python client. Includes code for listing models, formatting output, and optional enhanced display with the tabulate library.

### prompt_engineering/reasoning_o1_openAI.ipynb
Focuses on advanced prompting and reasoning with OpenAI's latest models (including o1 and GPT-4 series). Shows how to list available OpenAI models, construct effective reasoning prompts, and use structured formats. Includes practical code for generating functions and outputs using reasoning models.

### prompt_engineering/prompt_engineering_amazon_bedrock.ipynb
Introduces prompt engineering with Amazon Bedrock's APIs, covering both the basic Invoke API and the more powerful Converse API. Demonstrates text summarization, multi-turn conversations, and function calling capabilities across various foundation models including Claude 3.7 Sonnet, Amazon Nova Pro, and Meta Llama 3.1. Includes practical examples of comparing results across different state-of-the-art models and working with AWS Bedrock's serverless infrastructure.

### tool_use/tooluse_anthropic.ipynb
Demonstrates how to build and use an agentic tool with Anthropic Claude. The notebook walks through defining a Wikipedia article retrieval tool, setting up a tool schema, and orchestrating a full agentic loop for question answering with external tool calls. It includes practical code for integrating the tool with Claude's API, handling tool use responses, and returning results to the model. Each step is explained with detailed markdown cells for clarity.
