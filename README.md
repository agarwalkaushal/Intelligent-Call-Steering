# Intelligent-Call-Steering

<h5>Module 1: Transcribing Streaming Audio</h5>

1. Set up a GCP Console project.
2. Enable the Google Speech-to-Text API for that project.
3. Click Create Credentials
4. Create a service account.
5. Download a private key as JSON.

After you have obtained the key in your system, replace the path of your .json file in the transcribe_streaming_mic.py file at line 14.

Before you run the code, make sure to have the dependecies installed:

````
pip install --upgrade google-cloud-speech
pip install pyaudio
````

Example usage:
````
python transcribe_streaming_mic.py
````