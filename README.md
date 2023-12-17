# Getting Started with Multimodal model - Gemini Pro and Gemini Pro Vision

This tutorial is intended for getting hands on quickly with Gemini Pro and Gemini Pro Vision.

- We will be using Google AI Studio library for Text to Text Examples and Image Question and Answering tasks.
- For Video Question and Answering, we will be using Vertex AI library.

## Prerequisites

- Have Anaconda install and is initialized to the terminal.

### Getting Google AI Studio API Key

- Go to [Google AI for Developers](https://ai.google.dev) and click on "Get API key Google AI Studio".
- Click on Get API Key followed by clicking Create API Key in new project or Create API Key in existing project.

### Creating Google Service Account

- Create Google Cloud Service Account - with the role of Vertex AI Adminstrator.
- Once the service account is created, click on that service account, followed by click on Keys, Add Key, select JSON and click on Create.

## Creating Conda Environment

1. Create new conda environment.

```bash
conda create -n google_gemini_environment python=3.11
```

2. Install the requirements

```bash
pip install -r requirements.txt
```

3. Activate the environment

```bash
conda activate google_gemini_environment
```

## Tutorials

All are documented in the Notebooks in the research folder.
