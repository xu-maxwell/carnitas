# Carnitas: Audio Processing Library
Carnitas is a Python package designed for the Laryngeal Tissue Engineering Lab at UCLA to process audio files and interact with cloud storage (e.g., Box). It provides utilities for working with various audio formats and automating file management tasks related to audio files.

## Features
* Recursive Audio File Discovery: Easily find audio files of various formats (.mp3, .wav, .flac, .ogg, .aac, .m4a) in nested directories.
* Cloud Storage Integration: Connect to Box for seamless file storage and retrieval.
* Audio Processing: Perform operations such as reading, writing, and analyzing audio signals.
* Signal Processing Tools: Detect peaks and other signal processing utilities using scipy.

## Installation
To install carnitas, use pip:

```bash
pip install carnitas
```

## Usage
Once installed, you can begin using the package by importing it and calling the begin() method:

```python
import carnitas
carnitas.begin()
```
## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to help improve the project.

