# Open Source, Actively Maintained Web Apps for LLMs 💬

Jump-start your LLM project by starting from an app, not a framework. This repository aggregates high-quality, functioning web applications for use cases including Chatbots, [Natural Language Interfaces](https://colinharman.substack.com/i/137091060/natural-language-interfaces-nli), Assistants, and Question Answering Systems. It compares projects along important dimensions for these use cases, to help you choose the right starting point for your application.

To ensure the utmost quality and usability, projects must adhere to the following criteria to be included:

- Licensed under Open Source terms 💸
- Actively Maintained, meaning updated within the past month or under active monitoring 🚨

The projects span a wide range of complexity, from straightforward API wrappers to production-ready systems with multi-source RAG backends, conversation logging, and authentication/user management. There should be something for almost every need.

## Project Submissions
Contributions are the backbone of this list! If you're aware of a project that meets our criteria but isn't listed, we'd love to hear about it. Please also notify us if any of the listed projects becomes unmaintained or changes its licensing. Additionally, if there's a project detail that you'd like to compare that's not currently tracked, submit an issue for it. Finally, if you're the maintainer of a project that's already listed and would like to update or modify the listing, submit it again with the desired modifications.

**To submit a project:**

1. [Create an issue](https://github.com/snowfort-ai/awesome-llm-webapps/issues/new?assignees=clharman&labels=new_project%2Cupdate%2Cremove&projects=&template=contribution.yaml&title=%5BLLM%5D%3A+).
2. Ensure your submission adheres to the listed criteria and includes all relevant details.
3. Submissions will be reviewed and the projects list will be updated within a day.

If you'd like to help maintain this project, contact [clharman](https://github.com/clharman) via email.

_Currently seeking submissions for:_

- _Lightweight chatbots_
- _Projects with advanced prompting_
- _Non-chatbot interfaces (question answering, etc)_
- _Projects with image support_
- _Projects in different languages e.g. Python only_

# Project Table

| Project                                                      | Demo                                   | Brief Description                                            | Architecture                                         | Conversation Context Carry | Conversation History | Authentication           | Model Support                                                | Rich Text Support | Image Support | (RAG) Search Engine            | (RAG) Show Sources | (RAG) Data ingestion               | Quick Deploy                 | Other Features                                               |
| ------------------------------------------------------------ | -------------------------------------- | ------------------------------------------------------------ | ---------------------------------------------------- | -------------------------- | -------------------- | ------------------------ | ------------------------------------------------------------ | ----------------- | ------------- | ------------------------------ | ------------------ | ---------------------------------- | ---------------------------- | ------------------------------------------------------------ |
| [Hugging Face Chat UI](https://github.com/huggingface/chat-ui) ![License](https://img.shields.io/github/license/huggingface/chat-ui) ![Language](https://img.shields.io/github/languages/top/huggingface/chat-ui) ![Forks](https://img.shields.io/github/forks/huggingface/chat-ui) | 🟢 [Link](https://huggingface.co/chat/) | Full featured chat interface                                 | SvelteKit, MongoDB                                   | 🟢                          | 🟢                    | 🟢 OpenID                 | Hugging Face Inference API, local, Amazon SageMaker          | 🟢                 | 🔴             | 🟢 Google search                | 🟢                  | 🔴                                  | 🟢 Hugging Face Spaces        | Theme configuration                                          |
| [Weaviate Verba](https://github.com/weaviate/verba) ![License](https://img.shields.io/github/license/weaviate/verba) ![Language](https://img.shields.io/github/languages/top/weaviate/verba) ![Forks](https://img.shields.io/github/forks/weaviate/verba)<br> | 🟢 [Link](https://verba.weaviate.io/)   | Chat interface for RAG applications                          | React frontend, FastAPI backend, Weaviate            | 🔴                          | 🔴                    | 🔴                        | OpenAI                                                       | 🟢                 | 🔴             | 🟢 Weaviate                     | 🟢                  | 🟢 Via CLI                          | 🟢 Docker                     | Semantic caching                                             |
| [Microsoft Azure Chat](https://github.com/microsoft/azurechat) ![License](https://img.shields.io/github/license/microsoft/azurechat) ![Language](https://img.shields.io/github/languages/top/microsoft/azurechat) ![Forks](https://img.shields.io/github/forks/microsoft/azurechat) | 🔴                                      | Azure-based private chat tenant over data and files          | Next.js, LangChain.js, CosmosDB                      | 🟢                          | 🟢                    | 🟢 NextAuth               | OpenAI                                                       | 🟢                 | 🔴             | 🟢 Azure Cognitive Search       | 🔴                  | 🟢 UI single-file upload            | 🟢 Azure                      |                                                              |
| [AWS GenAI LLM Chatbot](https://github.com/aws-samples/aws-genai-llm-chatbot) ![License](https://img.shields.io/github/license/aws-samples/aws-genai-llm-chatbot) ![Language](https://img.shields.io/github/languages/top/aws-samples/aws-genai-llm-chatbot) ![Forks](https://img.shields.io/github/forks/aws-samples/aws-genai-llm-chatbot) | 🔴                                      | AWS-based chatbot with RAG and selectable LLMs               | React frontend, LangChain.js, cloud services backend | 🟢                          | 🟢                    | 🟢 Amazon Cognito         | Bedrock, SageMaker, Hugging Face Inference Endpoints, OpenAI, Anthropic, AI21, Cohere | 🔴                 | 🔴             | 🟢 Postgres/ Kendra/ OpenSearch | 🟢                  | 🟢 UI file upload                   | 🟢 AWS                        | User-selectable model and search backend                     |
| [PrivateGPT](https://github.com/imartinez/privateGPT) ![License](https://img.shields.io/github/license/imartinez/privateGPT) ![Language](https://img.shields.io/github/languages/top/imartinez/privateGPT) ![Forks](https://img.shields.io/github/forks/imartinez/privateGPT) | 🔴                                      | API, pipeline, and UI for RAG applications. Supports private models. | FastAPI, LlamaIndex, Gradio                          | 🟢                          | 🔴                    | 🔴                        | Local, OpenAI, Sagemaker                                     | 🔴                 | 🔴             | 🟢 Qdrant, Chroma               | 🟢                  | 🟢 UI file upload                   | 🔴                            |                                                              |
| [Ollama Web UI](https://github.com/ollama-webui/ollama-webui) ![License](https://img.shields.io/github/license/ollama-webui/ollama-webui) ![Language](https://img.shields.io/github/languages/top/ollama-webui/ollama-webui) ![Forks](https://img.shields.io/github/forks/ollama-webui/ollama-webui) | 🔴                                      | Full featured GPT clone                                      | Sveltekit, Ollama backend                            | 🟢                          | 🟢                    | 🟢                        | Local: Any Ollama supported model                            | 🟢                 | 🟢             | 🔴                              | 🔴                  | 🔴                                  | 🟢 Docker Compose             |                                                              |
| [Azure GPT-RAG](https://github.com/Azure/GPT-RAG) ![License](https://img.shields.io/github/license/Azure/GPT-RAG) ![Language](https://img.shields.io/github/languages/top/Azure/GPT-RAG) ![Forks](https://img.shields.io/github/forks/Azure/GPT-RAG) | 🔴                                      | Enterprise-ready RAG framework                               | All-Azure services                                   | 🟢                          | 🟢                    | 🟢 Azure Active Directory | OpenAI                                                       | 🟢                 | 🔴             | 🟢 Azure Cognitive Search       | 🟢                  | 🟢 Data source connections          | 🟢 Azure                      | Microsoft Teams bot integration, costs estimator             |
| [Danswer](https://github.com/danswer-ai/danswer) ![License](https://img.shields.io/github/license/danswer-ai/danswer) ![Language](https://img.shields.io/github/languages/top/danswer-ai/danswer) ![Forks](https://img.shields.io/github/forks/danswer-ai/danswer)<br> | 🔴                                      | Full featured RAG system with prebuilt data connectors for many source systems | FastAPI, Next.js, Vespa, Postgres, Celery            | 🟢                          | 🟢                    | 🟢                        | OpenAI, Local                                                | 🟢                 | 🔴             | 🟢 Vespa                        | 🟢                  | 🟢 Selection of data connectors     | 🟢 Docker Compose, Kubernetes | Slack bot                                                    |
| [LLM Answer Engine](https://github.com/developersdigest/llm-answer-engine) ![License](https://img.shields.io/github/license/developersdigest/llm-answer-engine) ![Language](https://img.shields.io/github/languages/top/developersdigest/llm-answer-engine) ![Forks](https://img.shields.io/github/forks/developersdigest/llm-answer-engine) | 🔴                                      | Perplexity style answer engine with web search               | React, LangChain.JS, Brave, Serper, OpenAI           | 🟢                          | 🔴                    | 🔴                        | Mixtral, Ollama, OpenAI                                      | 🔴                 | 🔴             | 🟢 Brave, Serper                | 🟢                  | 🔴 Web search, not ingestion        | 🔴                            |                                                              |
| [Dify](https://github.com/langgenius/dify) ![License](https://img.shields.io/github/license/langgenius/dify) ![Language](https://img.shields.io/github/languages/top/langgenius/dify) ![Forks](https://img.shields.io/github/forks/langgenius/dify) | 🔴                                      | App development platform for GenAI                           | Next.js, Flask, Postgres                             | 🟢                          | 🟢                    | 🟢                        | Various                                                      | 🟢                 | 🟢             | 🟢 Various                      | 🟢                  | 🟢 UI file upload                   | 🟢 AWS, Kubernetes            | Agents, observability                                        |
| [Flowise](https://github.com/FlowiseAI/Flowise) ![License](https://img.shields.io/github/license/FlowiseAI/Flowise) ![Language](https://img.shields.io/github/languages/top/FlowiseAI/Flowise) ![Forks](https://img.shields.io/github/forks/FlowiseAI/Flowise) | 🔴                                      | Drag-and-drop LLM flow builder                               | React, Node                                          | 🟢                          | 🟢                    | 🟢                        | Various                                                      | 🔴                 | 🔴             | 🟢 Various                      | 🟢                  | 🟢 UI file upload                   | 🟢 AWS, Kubernetes            | GUI/no-code LLM app logic builder                            |
| [RAGFlow](https://github.com/infiniflow/ragflow) ![License](https://img.shields.io/github/license/infiniflow/ragflow) ![Language](https://img.shields.io/github/languages/top/infiniflow/ragflow) ![Forks](https://img.shields.io/github/forks/infiniflow/ragflow) | 🟢 [Link](https://demo.ragflow.io/)     | Enterprise-RAG engine based on deep document understanding   | React, DeepDoc                                       | 🟢                          | 🟢                    | 🟢                        | Various                                                      | 🟢                 | 🟢             | 🟢 Elasticsearch/Infinity       | 🟢                  | 🟢 UI file upload / file management | 🟢 Docker Compose             | Document structure recognition / Table structure recognition |

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=snowfort-ai/awesome-llm-webapps&type=Date)](https://star-history.com/#snowfort-ai/awesome-llm-webapps&Date)
