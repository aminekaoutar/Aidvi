# Aidvi

# AIdvi - AI-Powered Virtual Assistant 🤖

A sophisticated virtual assistant platform that leverages Large Language Models (LLMs) to create customizable AI chatbots. Built with modern web technologies and AI capabilities.

## ✨ Features

### 🤖 Smart AI Capabilities
- **Multi-format Document Processing** - PDF, DOCX, CSV, YouTube transcripts, and web content
- **Conversational Memory** - Maintains context across conversations
- **Customizable Personalities** - Tailor bot behavior and responses
- **Real-time Processing** - Instant responses with LangChain orchestration

### 💼 User Management
- **Secure Authentication** - Flask-based session management
- **Subscription Plans** - Stripe-integrated billing system
- **Multi-bot Support** - Create and manage multiple AI assistants
- **Token-based Usage** - Track and manage AI usage

### 🎨 Modern Interface
- **React.js Frontend** - Responsive and intuitive user interface
- **Real-time Chat** - Smooth messaging experience
- **Mobile Responsive** - Works seamlessly across all devices

## 🛠 Tech Stack

### Backend
- **Flask** - Python web framework
- **LangChain** - LLM orchestration
- **OpenAI GPT** - Core AI capabilities
- **PostgreSQL/MySQL** - Database management
- **Redis** - Session storage

### Frontend
- **React.js** - Modern UI framework
- **Tailwind CSS** - Styling and responsive design
- **Stripe.js** - Payment processing

### AI & Processing
- **OpenAI Embeddings** - Text vectorization
- **FAISS** - Vector similarity search
- **PyPDF2/Docx** - Document processing
- **YouTube Transcript API** - Video content extraction

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- Node.js 16+
- MySQL/PostgreSQL
- Redis

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/aidvi.git
cd aidvi

2. **Backend Setup**
# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Environment configuration
cp .env.example .env
# Add your API keys in .env
