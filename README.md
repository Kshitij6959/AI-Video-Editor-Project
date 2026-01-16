# AI-Powered Video Auto-Editor

## Project Overview
**Module E: AI Applications**
This project automates the video editing process by removing silence and "dead air" from raw footage. It utilizes OpenAI's Whisper model for accurate speech detection, ensuring that cuts are based on semantic content rather than just volume thresholds.

## Features
* **Automated Silence Removal:** Detects non-speech segments and removes them.
* **AI Transcription:** Uses OpenAI Whisper (Base model) for timestamp generation.
* **Python-Based:** Built using `moviepy` and `whisper`.

## How to Run
1.  Open the `AI_Video_Editor.ipynb` notebook.
2.  Upload your raw video as `input_video.mp4`.
3.  Run all cells to generate `final_cut.mp4`.

## Dependencies
* Python 3.x

* See `requirements.txt` for library details.
