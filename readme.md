# Mashup-102117012

## Description
Mashup is a Python package for creating mashups of audio files from YouTube videos. It allows you to download audio from YouTube videos related to a specific artist, cut them to a specified duration, and merge them into one audio file.

## Installation
You can install Mashup-102117012 via package manager **pip**:

`pip install Mashup-102117012`


## Usage
To use Mashup, you can execute a Python script with the following arguments:
- `search_keyword`: The name of the artist or the search keyword to find related YouTube videos.
- `num_of_videos`: The number of YouTube videos to download audio from.
- `audio_duration`: The duration (in seconds) of the audio clips to be cut from each video. (Must be >= 20 seconds)
- `output_file_name`: The name of the output audio file.

Here's an example of how to use Mashup:

```bash
python sample.py "eminem" 20 20 output.mp3
```


## Dependencies:
-   Selenium
-   Pydub
-   Pytube

