# natbot-ng

Drive a browser with GPT-4-Turbo

Here's a demo: https://twitter.com/natfriedman/status/1575631194032549888

Lots of ideas for improvement:
- Better prompt
- Prompt chaining
- Make a recorder to collect human feedback and do better few-shot
- Better DOM serialization
- Let the agent use multiple tabs and switch between them

Improvements welcome!

## Setup

Set the OpenAI API key in the `OPENAI_API_KEY` environment variable:

```sh
export OPENAI_API_KEY="xxx"
```

Install the requirements with pip:

```sh
pip install -r requirements.txt
```

Install the browser driver:

```sh
playwright install
```

## Run

```sh
python natbot.py
```
