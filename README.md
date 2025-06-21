# Learning OpenAI's Whisper for Speech-to-Text

This repository documents my process of learning how to use OpenAI's Whisper, a powerful and open-source tool for automatic speech recognition (ASR).

## Project Overview

The primary goal of this project was to understand the fundamentals of Whisper and use it to transcribe audio files into text. This work was completed by following an excellent YouTube tutorial from Kevin Stratvert, which provided a clear, step-by-step guide.

-   **Tutorial Link:** [How to Use OpenAI Whisper for Free - Speech to Text AI Tutorial](https://www.youtube.com/watch?v=J30p2_eJ4M4)

## Environment

To avoid the need for powerful local hardware, this entire project was developed and executed using **Google Colaboratory**. This platform provides free access to GPUs in the cloud, making it an ideal environment for running machine learning models like Whisper directly in the browser.

## What is Whisper?

Whisper is an automatic speech recognition system developed by OpenAI. It was trained on a massive and diverse dataset of audio, enabling it to accurately transcribe speech from various languages, accents, and even noisy environments. [1]

## Process Summary

The key steps involved in this project were:
1.  Setting up a new notebook in Google Colaboratory.
2.  Connecting Google Colab to Google Drive and enabling the GPU hardware accelerator.
3.  Installing Whisper and its dependency, FFmpeg, using `pip` and `apt`.
4.  Uploading an audio file to the Colab environment.
5.  Running the Whisper command with the desired model (e.g., `base`, `small`, `medium`) to generate the transcription.
6.  Downloading the resulting text (.txt) and caption (.srt, .vtt) files.

Thank you for visiting my repository!
