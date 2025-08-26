# 🧠 PromptMind - Customizable Local AI Desktop Application

## 📋 Description

PromptMind is a desktop application that integrates a local AI model, allowing users to:

- ✅ **Customize** with a system prompt  
- ✅ **Enrich** with their own knowledge base  
- ✅ **Use** as a specialized assistant in any chosen field  
- ✅ **Ensure** full autonomy and data privacy  

## 🚀 Features

### 📦 AI Profile Management
- Create specialized profiles (Law, Medicine, IT, Cybersecurity, etc.)  
- Custom configuration for each profile  
- Adjustable system prompt and parameters  

### 🧠 Local AI Integration
- Supports models via **Ollama** (LLaMA, Mistral, CodeLlama, etc.)  
- Adjustable parameters: temperature, top_p, max tokens  
- 100% local processing without the cloud  

### 📚 Knowledge Base
- Import documents: **PDF, DOCX, TXT, Markdown**  
- Vector indexing with **FAISS**  
- **RAG** engine (Retrieval-Augmented Generation)  
- Semantic search within documents  

### 💬 Conversational Interface
- Modern chat with **Markdown rendering**  
- **Temporary attachments**: Upload files for one-time analysis  
- Paperclip button (📎) to attach files without adding them to the knowledge base  
- Dark/Light mode support  

### 🤖 Supported Models

**Automatic Model Management:**
- ✅ Automatic detection of installed models  
- ✅ Automatic download if model is missing  
- ✅ Functionality test after loading  
- ✅ Clear error messages in case of issues  

**Tested and Recommended Models:**
- **Llama 3** (`llama3:latest`) - Optimal performance  
- **Llama 2** (`llama2`) - Stable default model  
- **Mistral** (`mistral`) - Versatile and efficient  
- **Code Llama** (`codellama`) - Development-focused  

## 🎯 Usage

USAGE INSTRUCTIONS:

1. STANDARD LAUNCH:  
   - Double-click `"Start_PromptMind.bat"`  
   - Wait for the interface to appear (may take 10–30 seconds)  
   - The backend starts automatically in the background  

2. ADVANCED LAUNCH (PowerShell):  
   - Right-click `"Start_PromptMind_Avance.ps1"`  
   - Select **"Run with PowerShell"**  
   - Follow the on-screen instructions  

3. IF THE INTERFACE REMAINS BLANK:  
   - Close the application  
   - Wait 5 seconds  
   - Relaunch using the startup script  
   - The backend may take time to fully initialize  

4. TROUBLESHOOTING:  
   - If the interface does not load after 1 minute:  
     * Close the application  
     * Restart your computer  
     * Relaunch PromptMind  

   - If the issue persists:  
     * Check that port **8000** is not in use  
     * Temporarily disable antivirus  
     * Run as administrator  

REQUIREMENTS:
- Windows 10/11 (64-bit)  
- Minimum 4 GB RAM  
- 2 GB free disk space  
- Internet connection required for AI models  

SUPPORT:  
If issues occur, check the logs in the application folder.  

=======================================================  
**PromptMind** - Your customizable local AI 🧠✨  
 
