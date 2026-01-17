# AI Video Editing Assistant

## Module
Module E – AI Applications

## Project Overview
This project implements a backend-heavy AI system that automates multiple
video editing tasks using computer vision, machine learning, and signal
processing techniques.

The system operates directly on raw video input and performs intelligent
analysis and editing without requiring manually labeled datasets.

## Features Implemented
- Frame extraction from video
- Scene boundary detection
- Face detection and identity clustering
- Character presence timeline
- Character-based clip generation
- Smart clip segmentation
- Automatic trailer generation
- Character importance scoring
- Audio extraction
- Speech-to-text caption generation
- Caption burning (hard subtitles)
- Grayscale video conversion
- Video super resolution (lightweight)

## Technologies Used
- Python
- PyTorch
- OpenCV
- FFmpeg
- Whisper (ASR)
- scikit-learn

## How to Run
1. Open the Jupyter Notebook:
   `AI_Video_Editing_Assistant_ModuleE.ipynb`
2. Run all cells from top to bottom.
3. Outputs (JSON, MP4, SRT files) will be generated automatically.

## Ethical Considerations
- The system does not assign real-world identities to detected faces.
- Face analysis may be affected by dataset bias.
- User consent is required for processing personal video content.

## Author
Ronit Mongia
