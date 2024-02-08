# Azure Cognitive Services and OpenAI Integration

This repository is a voice bot that you can talk to and that responds in voice.
The bot integrates Azure Cognitive Speech Services and Azure OpenAI to create an interactive voice-based application. 
The conversation history is managed, so that you can have a realy conversation with the bot.

## Features
- **Speech Recognition**: Converts spoken language into text using Azure Cognitive Speech-to-Text service.
- **OpenAI Integration**: Utilizes Azure's OpenAI service for intelligent and context-aware conversation generation.
- **Speech Synthesis**: Converts text responses into natural-sounding speech.
  
## Prerequisites

Before you begin, ensure you have met the following requirements:

- An Azure account with active subscriptions for Cognitive Services, and Azure OpenAI.
- Python 3.9+ installed on your machine.

## Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/yourgithubusername/azure-cognitive-openai-integration.git
cd azure-cognitive-openai-integration

Install the required Python packages:
pip install -r requirements.txt


Configuration
Azure Services Setup: Ensure you have created and configured the required Azure services (Cognitive Services, Key Vault, and OpenAI). 
Note down your Key Vault name, and the keys and endpoints for Cognitive Services and OpenAI.

Environment Variables: Set up the following environment variables or modify the provided config.py (if created) with your Azure resources' details:

Make sure you have an OpenAI GPT-4 model deployed with deployment name "GPT-4" / or change the variable as needed
SPEECH_SERVICE_REGION: The region of your Azure Speech Service.
(Optionally, any other variables you find necessary for your setup).
