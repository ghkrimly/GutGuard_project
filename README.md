# GutGuard: AI-Powered IBS Assistant
Senior Project for Effat University students: Nada Khalefa - Sahar Albardawil - Ghayah Krimly

## Introduction
GutGuard is an intelligent web-based system designed to empower IBS patients with AI-driven health guidance. By integrating medical report analysis, symptom tracking, and personalized meal planning, it acts as a 24/7 digital assistant to:

 **Decipher medical reports** (PDFs) via OCR and biomarker extraction  
 **Suggest Low-FODMAP meals** tailored to your health profile  
 **Track symptoms** and identify dietary triggers over time  

## 🛠 Core Technology Stack
| Component | Technology | Purpose |
|-----------|------------|---------|
| **AI Chatbot** | Mistral-7B (via Ollama) | Natural language understanding |
| **Backend** | FastAPI (Python) | Document processing & API logic |
| **Frontend** | HTML/CSS/JS | User interface |
| **Medical NLP** | Tesseract OCR + MER | Biomarker extraction |

## Prerequisites

Before running this project, ensure you have the following installed:

- [Ollama](https://ollama.ai/) (Required for Mistral-7B)
- [Python](https://www.python.org/downloads/) (3.7 or higher recommended)
- [FastAPI](https://fastapi.tiangolo.com/)
- [Git](https://git-scm.com/downloads) (Optional, for version control)

If using VSCode:
- [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) (for web development)

## Installation

1. **Download the project**:
   - Click "View raw" to download the ZIP file
   - Extract the contents to your preferred directory

2. **Set up Ollama with Mistral-7B**:
   ```bash
   ollama pull mistral
   ollama run mistral
