# YouTube Video Transcription and Media Processing

This repository contains Jupyter Notebooks for transcribing YouTube videos, processing audio and video files, and utilizing various models to transcribe speech into text in different formats.

## Notebooks

### 1. `transcritor_en_pt_via_youtube_api.ipynb`
This notebook handles transcription of YouTube videos, using the YouTube API and Whisper for English and Portuguese languages.

#### Key Features:
- Connects to the YouTube API to retrieve video data.
- Downloads video/audio and processes the files.
- Utilizes the Whisper model to generate transcriptions for both English and Portuguese languages.

#### Required Libraries:
- `whisper`
- `youtube_dl`
- `torch`
- `ffmpeg`
- `pydub`

### 2. `trascritor_videos_youtube.ipynb`
This notebook focuses on downloading and transcribing YouTube videos.

#### Key Features:
- Downloads YouTube videos or audio files using the `youtube_dl` library.
- Processes audio with Whisper to generate transcriptions.

#### Required Libraries:
- `whisper`
- `youtube_dl`
- `ffmpeg`
- `tqdm`

### 3. `transcritor_formatos_diversos.ipynb`
This notebook expands the transcription functionality to support a variety of audio and video formats, beyond YouTube.

#### Key Features:
- Accepts various media formats, including `.mp3`, `.mp4`, `.wav`, `.opus`, and more.
- Uses `pydub` and `ffmpeg` to convert and process files for transcription.
- Outputs text in multiple formats, including `.txt`.

#### Required Libraries:
- `whisper`
- `ffmpeg`
- `pydub`

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/your_repository.git
   cd your_repository
   
Install the required Python packages:

bash
Copiar código
pip install -r requirements.txt
Run the notebooks using Jupyter or Google Colab.

Dependencies
The following libraries are required to run these notebooks:

whisper
ffmpeg
torch
youtube_dl
pydub
tqdm
How to Use
Open the notebook in Jupyter or Google Colab.
Follow the steps provided in each notebook to transcribe videos or audio files.
Transcriptions will be saved in .txt format in the specified directory.
