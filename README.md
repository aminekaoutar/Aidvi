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
- MySQL
- Redis

### Installation & Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/aidvi.git
cd aidvi

# Backend Setup
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

# Database Setup
mysql -u root -p -e "CREATE DATABASE aidvi;"

# Frontend Setup
npm install

# Create environment file
cat > .env << EOL
OPEN_AI_API_KEY=your_openai_api_key_here
STRIPE_SECRET_KEY=your_stripe_secret_key_here
SECRET_KEY=your_flask_secret_key_here
SQLALCHEMY_DATABASE_URI=mysql://root:@localhost/aidvi
EOL


# Run the application
python app.py
# In new terminal: npm start
```
📁 Project Structure
text
aidvi/
├── app.py                 # Main Flask application
├── config.py             # Application configuration
├── models.py             # Database models
├── aidvi_functions.py    # Core AI processing functions
├── atawich.py           # Additional API routes
├── requirements.txt      # Python dependencies
├── package.json         # Node.js dependencies
└── React Components/    # Frontend components
    ├── App.jsx
    ├── ChatBot.jsx
    ├── Account.jsx
    └── Subscription.jsx
🔧 Configuration
Create a .env file in the root directory with:

env
OPEN_AI_API_KEY=your_openai_api_key
STRIPE_SECRET_KEY=your_stripe_secret_key
SECRET_KEY=your_flask_secret_key
SQLALCHEMY_DATABASE_URI=mysql://root:@localhost/aidvi
Supported File Types
PDF Documents - Text extraction and processing

DOCX Files - Word document parsing

CSV Data - Tabular data analysis

YouTube URLs - Transcript extraction

Web URLs - Content scraping

💡 Usage
Creating a New Bot
Register/Login to your account

Navigate to "Create New Bot"

Configure bot personality and settings

Upload training documents

Start chatting!

API Endpoints
POST /register - User registration

POST /login - User authentication

POST /create_bot - Create new AI assistant

POST /get_answer - Get bot responses

POST /create_subscription - Manage subscriptions

🎯 Use Cases
🏢 Business Applications
Customer support automation

Employee training assistants

Document analysis and Q&A

Knowledge base management

👨‍💻 Personal Use
Study assistants

Research companions

Content creation helpers

Personal knowledge management

🤝 Contributing
Fork the repository

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request
