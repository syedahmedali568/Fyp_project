## Features

- Record audio input from users in chunks.
- Transcribe the recorded audio using a pre-trained AI model.
- Interact with the AI model to generate responses based on user input.
- Utilizes a knowledge base for context-aware responses.

## Prerequisites

Before running the code, ensure you have the following dependencies installed:

- Python above 3.8
- `pyaudio`
- `numpy`
- `faster_whisper` (Installable via pip)
- `chromadb` (Installable via pip)
- Other dependencies specified in `requirements.txt`

## Usage

1. Clone this repository to your local machine.

2. Install the dependencies using pip.

   ```bash
   pip install -r requirements.txt

3. Run the main script app.py.

   ```bash
   python app.py

4. Follow the prompts to interact with the voice assistant. Speak into the microphone when prompted.

## Configuration
- You can adjust the default model size and chunk length in the script as per your requirements.
- Modify the paths and settings related to the knowledge base and AI model if needed.
- Place your PDF knowledge base file at `./rag/knowledgeBase.pdf` for the RAG system to use.

## Notes
- Ensure that your system's microphone is correctly configured and accessible by the script.
- Make sure to handle exceptions and errors gracefully, especially during audio recording and transcription processes.