# 🤖  Meeting Summarizer Agent

Automated AI agent that processes meeting transcripts and generates summaries using n8n + Mistral.

## 🌟 Features
- 🕒 Scheduled daily processing (12:05 PM)
- 🎙️ Whisper.cpp audio-to-text conversion
- 🧠 Mistral AI summarization
- 📂 Automatic file management

## 🔧 Tools Used
| Tool | Purpose |
|------|---------|
| **n8n** | Workflow Automation | 
| **Whisper.cpp** | Speech-to-Text 
| **Mistral** | AI Summarization | 

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
