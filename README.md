# 🎙️ YouTube Transcript MCP Server

A lightweight **MCP (Model Context Protocol) server** that downloads audio from YouTube videos, transcribes it using **AssemblyAI**, and makes the transcript accessible for summarization, Q&A, or other AI-powered tasks.

---

## 🚀 Features

- 🔑 **Bearer Token Authentication** for secure access  
- 🎧 **Download YouTube Audio** with `yt-dlp`  
- 📝 **Transcribe audio** via [AssemblyAI](https://www.assemblyai.com/)  
- ⚡ **Async support** for efficient background processing  
- 🛠️ **MCP Tool Integration** for AI agent workflows  

---

## 📂 Project Structure
├── media/ # Stores downloaded audio files
├── server.py # Main MCP server script
├── requirements.txt # Python dependencies
├── .env # Environment variables
└── README.md # Project documentation


---

## 🔧 Installation

1.  **Clone this repository**
    ```bash
    git clone [https://github.com/your-username/youtube-transcript-mcp.git](https://github.com/your-username/youtube-transcript-mcp.git)
    cd youtube-transcript-mcp
    ```

2.  **Create a virtual environment**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use: venv\Scripts\activate
    ```

3.  **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

---

## ⚙️ Environment Setup

Create a `.env` file in the root directory and add the following:

    ```env
    AUTH_TOKEN=your_auth_token
    MY_NUMBER=your_identifier
    ASSEMBLY_AI_API_KEY=your_assemblyai_key


