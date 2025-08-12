# Chirp 3: HD voices

View the available voice names here: https://cloud.google.com/text-to-speech/docs/chirp3-hd

This assumes you already have a GCP account with Chirp3 Voices enabled

## Set-up
* Download Google Cloud CLI: https://cloud.google.com/sdk/docs/install
* Sign-in by running `gcloud auth login` or `gcloud auth application-default login` and logging in the account with GCP permissions for the resource
* If you don't have Python 3.x on your local, Download the latest Python https://www.python.org/downloads/
* on your command line, navigate to this folder and run `pip install -r requirements.txt`

## Generating Audio
* open tts.py and change the text on line 5
* on your command line, navigate to this folder and run `python tts.py`
* it will generate a new file called output.mp3