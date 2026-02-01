# Building Autonomous AI Agents — Masterclass Preparation

Welcome to the **preparation page** for the upcoming masterclass on building autonomous AI agents.  
Before we start, please go through the required setup and create the necessary accounts — this will help you fully participate in the hands-on session.

### Objective
The goal of this masterclass is to move beyond prototypes and learn how scalable AI automation is built inside enterprise environments. You will see how systems like **n8n**, **Docker**, **Supabase**, and **OpenRouter** can be combined to create flexible and production-ready AI agents.

### Required Tools
Please ensure the following setup is completed before the masterclass:

To get the most out of our time and move from a "beginner" to a "pro" perspective, I invite you to do a **mini-research** on the following topics:

- **Docker** – Installed and running on your local machine.  
  Used for isolation and seamless deployment of the services we'll create.  
  [Run Docker](https://www.docker.com/get-started/)
  
- **OpenRouter account** – Free registration.  
  This will give you access to multiple LLM endpoints used during exercises.  
  [Create an account](https://openrouter.ai/)
  
- **Supabase account** – Free tier is enough.  
  We will use it as a lightweight backend for storing and retrieving structured data.  
  [Create an account](https://supabase.com/)
  
- **n8n container** – Deploy on your docekr.  
  Try deploying an n8n container and opening the UI in your browser.
  [Learn about n8n](https://osher.com.au/blog/how-to-host-n8n-with-docker/)

### Recommended Hardware
- **RAM:** at least 16 GB  
- **GPU:** optional, but having a dedicated GPU will be a strong advantage for local model runs (e.g., via Ollama or similar).

### During the Masterclass
We will:
- Develop a minimal, but functional, AI agent step-by-step.
- Explore how **n8n** orchestrates logic, tools, and workflows.  
- Deploy and test the agent inside Docker containers.  
- Connect external data services and APIs.  
- Discuss scaling and integration within large enterprise infrastructures (e.g., how Big copmpany or similar companies approach automation pipelines).

All deployment details and code examples will be clarified during the session.

### Before the Masterclass (Optional but Recommended)
If you want to get more out of the session, take some time to explore the tools we'll be using:
- Try to understand how containers talk to each other within a network (e.g., how n8n can reach a local Ollama instance).
- Read the documentation for **n8n**, **Docker**, or **Supabase**.  
- Try running a simple workflow in n8n or deploying a basic container with Docker.  
- Experiment with calling an LLM through **OpenRouter**.
- Look into "LangChain nodes" vs "Regular nodes". How does n8n handle state in a long-running conversation?
- Compare the latency. When is it better to run a model locally versus using a free cloud API?
- Explore what "Vector Store" is. Why do we need it for an AI Agent instead of a regular SQL table?

**Why do this?**
If you come prepared with these basic concepts in mind, our discussion during the masterclass won't be about "how to click buttons," but about **architecting high-level solutions, optimizing performance, and solving real enterprise challenges.**

### Repository Link
The full technical guide and setup instructions will be available in this repo

Let's get ready to transform ideas into real, working AI projects!
