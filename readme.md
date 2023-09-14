# Rubber Ducky assistant

Stuck on a tricky problem? Not sure what you need to implement a new feature? Talk it out!

## Project primary goals

* Write a program that can be on any computer with an attached microphone and speaker
* The program will respond to audio prompts that begin with a trigger keyword
* Audio prompts are transcribed to text
* Prompt transcriptions are sent to OpenAI through their API
* OpenAI API responses are passed through a text-to-speech API
* The response from the text-to-speech API is played back over an attached audio output device

## Project Stretch goals

* The keyword can be customized
* The project can be configured with budget/credit constraints for the associated API services
* The project will include default audio output for API failures
* The project will include default audio output when budget constraints would be exceeded
* The speech recognition engine should be swappable
* The text to speech engine should be swappable
* API integrations to chat services (Slack, Discord, etc.) to keep a longer lasting copy of conversations

## Getting started

1. Run the `setup.sh` script to set up your local virtual environment and install the project requirements.
