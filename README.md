# ThinkingPsychologist

Welcome to **ThinkingPsychologist**, an innovative application powered by Falcon LLM, designed to act as a virtual psychologist. This app allows users to explore their psychology through storytelling.

By analyzing the narratives created by users in response to a series of images, ThinkingPsychologist offers insights into personality traits, emotional states, and other psychological aspects.

## Features

### Image-Based Storytelling
Users are presented with a series of images and are asked to record a story based on each image. This method helps in revealing underlying thoughts, feelings, and perceptions.

### Audio Recording & Transcription
The app records the user's voice as they narrate their story. These recordings are then transcribed using an open-source model.

### AI-Driven Analysis
Leveraging the powerful Falcon LLM, the application generates a detailed psychology assessment report. The report includes evaluations of personality traits, emotional states, key observations, and personalized recommendations.

### PDF Report Generation
Users receive a personalized PDF report summarizing their psychological analysis, including actionable insights and recommendations.

## How It Works

### Introduction
Users start by reading through the introductory page, which explains the process and instructions.

### Storytelling Phase
Users view a series of images, one at a time, and record a story for each image.

### Analysis Phase
The app transcribes the audio recordings and analyzes the stories using Falcon LLM to generate a psychology assessment.

### Report Generation
A comprehensive PDF report is generated and made available for download. This report includes an overall assessment, detailed personality traits, and recommendations for personal growth.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```

2. Navigate into the project directory:

    ```bash
    cd your-repo-name
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

## Running the App

To run the Streamlit app, use the following command:

```bash
streamlit run app.py
