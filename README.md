# AI Speech Intelligence System Using Whisper for Meeting Summarization

## Overview
This project explores how a pretrained speech foundation model can be used for speech intelligence tasks. The system takes spoken audio as input, transcribes it using Whisper, and produces useful outputs such as a summary, action items, and keywords.

## Problem Description
Speech-based information is common in meetings, lectures, and project updates, but manually reviewing audio takes time. This project demonstrates how AI can convert speech into structured and useful information automatically.

## Business Value
This system can save time, improve note-taking, and help users quickly identify the most important information from spoken updates. It is relevant for meeting assistants, lecture support systems, and productivity tools.

## Input Used
The project used a short self-recorded voice note describing project progress and next steps. The audio was converted into WAV format before transcription.

## Model Used
- OpenAI Whisper Small
- Python
- Google Colab

## Pipeline
1. Upload audio
2. Convert audio to WAV
3. Transcribe with Whisper
4. Generate summary
5. Extract action items
6. Extract keywords
7. Compare baseline vs improved output
8. Evaluate results

## Baseline Output
The baseline system produced only the raw transcript.

## Improved Output
The improved system produced:
- transcript
- summary
- action items
- keywords

## Results
### Transcript
Today we reviewed the progress of the project and discussed the next steps. We finished the first part of the system and tested the initial model output. We still need to improve the evaluation section, update the slides and upload the final files to GitHub. By tomorrow we should complete the demo video, review the results and prepare for the final submission.

### Summary
Today we reviewed the progress of the project and discussed the next steps. We finished the first part of the system and tested the initial model output. We still need to improve the evaluation section, update the slides and upload the final files to GitHub.

### Action Items
1. Improve the evaluation section
2. Update the slides
3. Upload the final files to GitHub
4. Complete the demo video
5. Review the results and prepare for the final submission

### Keywords
final, today, reviewed, progress, project, discussed, next, steps

## Evaluation
- Transcription Quality: 5/5
- Summary Quality: 4/5
- Action Item Usefulness: 4/5
- Latency / Efficiency: 3/5

## Limitations
The project worked best with clear short speech. Action item extraction was rule-based, so some results required interpretation. CPU execution was slower than GPU execution.

## Libraries Used
- openai-whisper
- Python
- Google Colab
- ffmpeg

## How to Run
1. Install dependencies
2. Upload an audio file
3. Convert the audio to WAV
4. Run Whisper transcription
5. Generate summary, action items, and keywords
6. Save outputs

## GitHub Link
https://github.com/Ibrahim17A/Quiz-Challenge-2

## Demo Video Link
https://youtu.be/ze_XmmZESyo

## AI Tool Disclosure
ChatGPT was used for planning, code guidance, README drafting, evaluation wording, and presentation support. Google Colab was used to run the project. Whisper was used for speech transcription.
