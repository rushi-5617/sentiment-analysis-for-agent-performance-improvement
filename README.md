# Sentiment Analysis for Agent Performance Improvement

## Overview
This project combines natural language processing and speech recognition to analyze customer feedback. It transcribes audio input into text and uses a pre-trained BERT model for multilingual sentiment analysis. The system is designed to help improve the performance of customer service agents by analyzing interactions and identifying trends in customer sentiment.

## Features
- **Audio Transcription**: Converts spoken feedback into text using `SpeechRecognition` and `pydub`.
- **Sentiment Analysis**: Uses Hugging Face's `nlptown/bert-base-multilingual-uncased-sentiment` model for multilingual sentiment classification.
- **Real-time Insights**: Analyze customer feedback in real time and classify sentiments as positive, negative or neutral.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - **Hugging Face Transformers**: For BERT-based sentiment analysis.
  - **PyTorch**: Backend framework for model inference.
  - **SpeechRecognition**: For transcribing audio to text.
  - **pydub**: For audio manipulation and playback.
  - **Google Speech-to-Text API**: Integrated through the `SpeechRecognition` library for transcription.
  - **OS**: For handling temporary files during audio processing.
