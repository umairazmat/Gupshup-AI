# Gup Shup AI “Your AI-Powered Conversational Partner””

// logo
<img src="/public/Logo.png" >

## Description

GupShupAI is an innovative, voice-to-voice conversational AI assistant that uses cutting-edge language models and speech processing technologies. It transcribes speech, generates responses using an LLM (Large Language Model), and converts the output to speech, making it a fully interactive and responsive chatbot.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Pip (Python package manager)

### Installation

## Clone the repository:

````bash
git clone https://github.com/umairazmat/Gupshup-AI
cd Gupshup-AI

## Set up a virtual environment:

```bash
python -m venv Gupshup-AI
````

## For Windows:

```bash
.\Gupshup-AI\Scripts\activate
```

## For Mac/Linux:

```bash
source Gupshup-AI/bin/activate
```

## Install the required packages:

```bash
pip install -r requirements.txt
```

## Create a .env file in the root directory with the following content:

```bash
OPENAI_API_KEY=your_actual_api_key
OPENAI_API_BASE=your_actual_api_key
GROQ_API_KEY=your_actual_api_key
```

## Run the application:

```bash
streamlit run .\app.py
```

## if script not run :

```bash
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

## Usage

- **Input**: Provide audio input through your microphone or upload an audio file.
- **Output**: GupShupAI will transcribe, process, and respond with both audio and text.

---

## Troubleshooting

- Verify that API keys are correctly set in the `.env` file.
- Ensure that the Python version and dependencies match the requirements.

---

## Contributing

1. **Fork the repository**
2. **Create a feature branch**

   ```bash
   git checkout -b feature/YourFeature
   ```

   3- **Commit your changes**

   ```bash
   git commit -m 'Add new feature'
   ```

4- **Push to the branch**
`bash
git push origin feature/YourFeature
    `bash

5- **Open a Pull Request**

## 📞 Contact

For queries or collaboration, please reach out at **hello@umairazmat.com**.
