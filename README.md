
# Virtual_AI_dr - AI-Driven Doctor

Welcome to the ai_dr project! This repository contains the code for an AI-driven application that uses the Llama-3 8B model to simulate a doctor. The AI can ask patients about their symptoms, provide diagnoses, and offer information about diseases, drugs, and treatments.

Demo-link->https://drive.google.com/file/d/1E-Th9jDThvelUOa1_Lpz9PztZc88BuwK/view?usp=sharing

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [API Key](#api-key)
- [Prompting](#prompting)

## Introduction

The ai_dr project leverages the powerful Llama-3 8B model from Replicate to create a virtual doctor. With the help of prompting, the AI can interact with patients, ask relevant queries, and provide detailed medical information.

## Features

- **Patient Interaction**: The AI asks patients about their symptoms and medical history.
- **Medical Diagnoses**: Based on the patient's input, the AI provides possible diagnoses.
- **Medical Information**: The AI can act as a medical researcher, offering information about diseases, drugs, and treatments.
- **Easy Integration**: Uses Replicate API for seamless model integration.

## Usage

To start using the AI-driven doctor, run the following command:

```bash
python Demo_Ai_bot.ipynb
```

Follow the on-screen instructions to interact with the AI.

## API Key

This project uses the Replicate API for accessing the Llama-3 8B model. You will need an API key from Replicate. Follow these steps to set it up:

1. Sign up on [Replicate](https://replicate.com/) and get your API key.
2. Create a `.env` file in the root directory of your project and add your API key:
   ```
   REPLICATE_API_KEY=your_api_key_here
   ```

## Prompting

The ai_dr project uses specific prompts to guide the Llama-3 8B model. Here are the primary prompts used:

1. **Doctor Interaction Prompt**:
   ```
   You are an AI doctor. Please ask the patient about their symptoms and medical history. Based on their responses, provide possible diagnoses and treatment options.
   ```

2. **Medical Researcher Prompt**:
   ```
   You are a medical researcher. Provide detailed information about diseases, drugs, and treatments based on the query.
   ```

Feel free to reach out if you have any questions or need further assistance. Happy coding!

