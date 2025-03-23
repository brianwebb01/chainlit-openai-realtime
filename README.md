Title: Realtime Assistant
Tags: [multimodal, audio]

# Open AI realtime API with Chainlit

This cookbook demonstrates how to build realtime copilots with Chainlit.

## Key Features

- **Realtime Python Client**: Based off https://github.com/openai/openai-realtime-api-beta
- **Multimodal experience**: Speak and write to the assistant at the same time
- **Tool calling**: Ask the assistant to perform tasks and see their output in the UI
- **Visual Presence**: Visual cues indicating if the assistant is listening or speaking

## Installation & Running

This code was tested with Python 3.10.16

1.  `pip install -r requirements.txt`
2.  set your OPENAI_API_KEY
3. boot the app with `chainlit run app.py -w`
4. Click on the voice button and say something like "show me a graph of the last 12 months performance of Apple Inc's Stock"