# Bible of AI Hackathon

## Productivity


### Vibe-coding with Gemini CLI

The Gemini CLI is a command-line interface for interacting with Google's Gemini models.

- **Gemini CLI Website:** [https://geminicli.com/](https://geminicli.com/)
- **Gemini CLI on GitHub:** [https://github.com/google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli)

### Firebase Studio

Firebase Studio is an integrated development environment that streamlines the process of building and deploying applications with Firebase. It offers a collaborative space for rapid prototyping, debugging, and iterating on your projects, making it an excellent tool for "vibe-coding" and quickly bringing ideas to life.

- **Firebase Studio Information:** [https://firebase.studio/](https://firebase.studio/)

### NotebookLM

NotebookLM is an AI-powered notetaker that helps you understand and explore complex information. It can summarize facts, explain complex ideas, and brainstorm new connections—all based on the sources you provide.

- **NotebookLM Website:** [https://notebooklm.google.com/](https://notebooklm.google.com/)


### Google AI Studio

Google AI Studio is a web-based tool that allows developers to quickly prototype and build generative AI applications. It provides a fast way to experiment with Google's large language models and offers multimodal access by connecting to your Google Cloud Project. While AI Studio is excellent for rapid prototyping, for more advanced features, MLOps capabilities, and a broader range of models, Vertex AI is recommended.

- **Google AI Studio Website:** [https://aistudio.google.com/](https://aistudio.google.com/)

## Model Supervised Fine-tuning

Supervised fine-tuning of Gemini models offers a cost-effective and rapid way to adapt models to specific tasks or domains. By providing a relatively small dataset of labeled examples, you can significantly improve model performance for your particular use case without the need for extensive retraining from scratch. This makes it an agile approach for achieving specialized AI capabilities.

- **About supervised fine-tuning for Gemini models:** [https://docs.cloud.google.com/vertex-ai/generative-ai/docs/models/gemini-use-supervised-tuning](https://docs.cloud.google.com/vertex-ai/generative-ai/docs/models/gemini-use-supervised-tuning)


## Agents

### Ultimate Guide to Building Agentic AI Systems

For technical founders and developers looking to build Agentic AI systems, Google has provided a no BS comprehensive technical guide which helps to make a decision to go Agentic AI or not. This guide covers core concepts, architectural components, and principles for creating reliable and responsible AI agents.

[Startup Technical Guide: Building Agentic AI Systems](https://services.google.com/fh/files/misc/startup_technical_guide_ai_agents_final.pdf)

### Agent Development Kit

- **ADK Documentation:** [https://google.github.io/adk-docs/](https://google.github.io/adk-docs/) - The official documentation for the Agent Development Kit.
- **Blueprint Agents Sample Repo:** [https://github.com/google/adk-samples](https://github.com/google/adk-samples) - A repository with sample agents to get you started.

### GenAI MCP Toolbox for Databases

The GenAI Toolbox is an open-source MCP (Multi-Cloud Platform) server for databases, designed to simplify the development of tools for AI agents to access data. It handles complexities like connection pooling and authentication, offering simplified development, better performance, enhanced security, and end-to-end observability.

- **GenAI Toolbox:** [https://github.com/googleapis/genai-toolbox](https://github.com/googleapis/genai-toolbox)

### Agent Engine

Agent Engine is a core component of Vertex AI Agent Builder that simplifies the path to production for AI agents. It handles critical operational aspects such as infrastructure management, scaling, security, and monitoring, allowing developers to focus on the agent's core capabilities.

- **Agent Engine Overview:** [https://docs.cloud.google.com/agent-builder/agent-engine/overview](https://docs.cloud.google.com/agent-builder/agent-engine/overview)


## Vertex AI

Vertex AI is a unified AI platform that helps you build, deploy, and scale machine learning (ML) models and AI applications. It provides a unified environment for the entire ML workflow, from data preparation to model training, deployment, and monitoring.

- **Vertex AI:** [https://cloud.google.com/vertex-ai](https://cloud.google.com/vertex-ai) - The official page for Vertex AI.
- **Vertex AI Search:** Vertex AI Search can act as a knowledge base for agents, allowing them to retrieve relevant information from various data sources to enhance their responses and decision-making capabilities.

## Cloud Run

Cloud Run is a fully managed compute platform that enables you to deploy and scale containerized applications quickly and easily. It abstracts away all infrastructure management, allowing you to focus on writing code. It's ideal for hosting stateless services, web applications, and APIs, including those powered by AI models.

- **Cloud Run Website:** [https://cloud.google.com/run](https://cloud.google.com/run) - The official page for Cloud Run.

## BigQuery

BigQuery is a fully managed, serverless data warehouse that enables super-fast SQL queries using the processing power of Google's infrastructure. Its serverless architecture means there's no infrastructure to manage, and it can store and analyze any kind of data (structured, semi-structured, or unstructured). This makes it incredibly convenient for agentic systems, as it can serve as a centralized, scalable, and flexible data repository for agent interactions, logs, and knowledge bases. Furthermore, BigQuery's native integration with Vertex AI allows for direct data enrichment by calling Vertex AI APIs within BigQuery, streamlining advanced analytics and AI-driven insights.

- **BigQuery Website:** [https://cloud.google.com/bigquery](https://cloud.google.com/bigquery) - The official page for BigQuery.

## Media Generation

### Veo 3.1

Veo is a text-to-video model from Google that generates high-quality videos from text prompts. It offers advanced creative controls, allowing users to guide video generation with reference images for character and style consistency, extend video clips, and create seamless transitions.

- **Veo Information:** [https://aistudio.google.com/models/veo-3](https://aistudio.google.com/models/veo-3)

### Imagen

Imagen is a text-to-image model that creates high-fidelity, photorealistic images from natural language prompts. It is known for its deep level of language understanding and ability to generate a wide range of creative and realistic images.

- **Imagen Information:** [https://cloud.google.com/vertex-ai/docs/generative-ai/image/overview](https://cloud.google.com/vertex-ai/docs/generative-ai/image/overview)

### Nano Banana

Nano Banana (officially Gemini 2.5 Flash Image) is a text-to-image model that also functions as an image editor. It allows for conversational, chat-based image editing, enabling users to transform photos with natural language descriptions. Unlike Imagen, which is primarily a text-to-image generator, Nano Banana excels at in-painting, out-painting, and other editing tasks, making it a versatile tool for both creating and modifying images.

### Lyria

You can use Lyria to generate new instrumental music tracks from a text prompt that you provide in the Google Cloud console or send in a request to the Gemini API in Vertex AI API.

- **Lyria Information:** [https://docs.cloud.google.com/vertex-ai/generative-ai/docs/music/generate-music](https://docs.cloud.google.com/vertex-ai/generative-ai/docs/music/generate-music)

## Gemini TTS

Gemini TTS (Text-to-Speech) is a powerful service that converts text into natural-sounding speech. It offers a wide range of voices and languages, allowing developers to create highly realistic and expressive audio content for various applications, such as voice assistants, audiobooks, and accessibility features.

- **Gemini TTS Documentation:** [https://docs.cloud.google.com/text-to-speech/docs/gemini-tts](https://docs.cloud.google.com/text-to-speech/docs/gemini-tts)

## Gemini Live API

Gemini Live API provides real-time, low-latency access to Gemini models, enabling interactive and dynamic AI experiences. This API is crucial for applications requiring immediate responses, such as live chatbots, interactive voice agents, and real-time content generation.

- **Gemini Live API Documentation:** [https://ai.google.dev/gemini-api/docs/live](https://ai.google.dev/gemini-api/docs/live)

