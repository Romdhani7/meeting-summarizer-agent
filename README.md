# Meeting Summarizer AI Agent

# 🤖 AI-Powered Meeting Summarizer Agent

![n8n Logo](https://n8n.io/favicon-32x32.png) ![Mistral Logo](https://example.com/mistral-logo.png) ![Whisper.cpp Logo](https://example.com/whisper-logo.png)

Automated pipeline that converts audio meetings → text transcripts → AI summaries using cutting-edge tools.

## 🌟 Features
- 🕒 Scheduled daily processing (12:05 PM)
- 🎙️ Whisper.cpp audio-to-text conversion
- 🧠 Mistral AI summarization
- 📂 Automatic file management

## 🔧 Tools Used
| Tool | Purpose | Logo |
|------|---------|------|
| **n8n** | Workflow Automation | ![n8n](https://n8n.io/favicon-32x32.png) |
| **Whisper.cpp** | Speech-to-Text | ![Whisper](https://example.com/whisper-logo.png) |
| **Mistral** | AI Summarization | ![Mistral](https://example.com/mistral-logo.png) |

## 🛠️ Setup  
1. Clone repo:  
`git clone https://github.com/yourusername/meeting-summarizer-agent.git`  
2. Import `Meeting_Summarizer_AI_Agent.json` into n8n  
3. Add Mistral API key in n8n credentials  

## 📸 Screenshots  
![Workflow](screenshots/workflow.png)  
*n8n automation workflow*

## 📝 Usage  
1. Upload meeting transcript (.txt)  
2. Execute workflow  
3. Find summary in `Results/` folder  
