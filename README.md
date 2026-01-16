# AI-Powered Video Auto-Editor

## Project Overview
**Module E: AI Applications**

This project automates the video editing process by removing silence and "dead air" from raw footage. It utilizes OpenAI's Whisper model for accurate speech detection, ensuring that cuts are based on semantic content rather than just volume thresholds.

## Features
* **Automated Silence Removal:** Detects non-speech segments and removes them efficiently.
* **AI Transcription:** Uses OpenAI Whisper (Base model) for precise timestamp generation.
* **Python-Based:** Built using `moviepy` for video processing and `whisper` for audio analysis.

## How to Run
1.  Open the `AI_Video_Editor.ipynb` notebook in Google Colab (or your local Jupyter environment).
2.  Upload your raw video file and rename it to `input_video.mp4`.
3.  Run all cells from top to bottom.
4.  The script will generate a processed video file named `final_ai_vlog.mp4`.

## Dependencies
* **Python 3.x**
* See `requirements.txt` for library details.

To install dependencies locally:
```bash
pip install -r requirements.txt

