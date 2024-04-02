<h1 align="center">🚀 Devika - AI SDE 👩‍💻</h1>

## Demos

https://github.com/Sahaj777/devika-ai-SDE/blob/main/devika-pygame-demo.mp4

## Key Features

- 🤖 Supports **Claude 3**, **GPT-4**, **GPT-3.5**, and **Local LLMs** via [Ollama](https://ollama.com). For optimal performance: Use the **Claude 3** family of models.
- 🧠 Advanced AI planning and reasoning capabilities
- 🔍 Contextual keyword extraction for focused research
- 🌐 Seamless web browsing and information gathering
- 💻 Code writing in multiple programming languages
- 📊 Dynamic agent state tracking and visualization
- 💬 Natural language interaction via chat interface
- 📂 Project-based organization and management
- 🔌 Extensible architecture for adding new features and integrations


## Quick Start

The easiest way to run the project locally:

1. Install `uv` - Python Package manager (https://github.com/astral-sh/uv)
2. Install `bun` - JavaScript runtime (https://bun.sh/docs/installation)
3. Install and setup `Ollama` (https://ollama.com/) (if you want don't want to use the local models then you can skip this step)

For ollama you need to install the [models](https://ollama.com/models)<br>
For API models, configure the API keys via setting page in UI. <br><br>

Then execute the following set of command:

```
ollama serve
https://github.com/Sahaj777/devika-ai-SDE/
cd devika/
uv venv
source .venv/bin/activate
uv pip install -r requirements.txt
playwright install --with-deps
cd ui/
bun install
bun run dev
cd ..
python3 devika.py
```

Docker images will be released soon. :raised_hands:

