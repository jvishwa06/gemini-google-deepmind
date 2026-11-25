# Gemini API Notebook

A notebook that shows how to call Google's Gemini models from Python with the `google-generativeai` library.

## What `Google-Gemini.ipynb` covers

- **Text generation** with `gemini-pro`: sends a prompt and displays the reply as Markdown.
- **Image understanding** with `gemini-pro-vision`: opens an image with Pillow, asks the model to describe it, and then asks a follow-up question about the image together with the picture.

## Setup

```bash
pip install -q -U google-generativeai
```

Get an API key from [Google AI Studio](https://aistudio.google.com/apikey) and put it in the `googleapi` variable at the top of the notebook. The image path in the vision cell points to a file on the author's computer, so change it to an image of your own.
