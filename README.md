# Langchain Medical ChatBot
## Introduction
The **Medical ChatBot using Langchain** is a powerful tool designed to provide medical information by answering user queries using state-of-the-art language models and vector stores. This README will guide you through the setup and usage of the Medical Bot.

---

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)

---

## Prerequisites

Before you can start using the Langchain Medical Bot, ensure the following prerequisites are met:

- **Python**: Version 3.6 or higher.
- **Required Python packages**:
  - `langchain`
  - `chainlit`
  - `sentence-transformers`
  - `faiss-cpu`
  - `PyPDF2` (for PDF document loading)
  - `CTransformers`
---

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/langchain-medical-bot.git
   cd langchain-medical-bot
2. Install the required Python packages:
   ```
   pip install -r requirements.txt
   pip install -U langchain-huggingface
   pip install tf-keras
   pip install -U transformers sentence-transformers tensorflow


## Usage
The Langchain Medical ChatBot can be used for answering medical-related queries. To use the bot, you can follow these steps:

1. Start the bot by running your application or using the provided Python script.

2. Send a medical-related query to the bot.

3. The bot will provide a response based on the information available in its database.

4. If sources are found, they will be provided alongside the answer.

5. The bot can be customized to return specific information based on the query and context provided.
