# 🚀 Fast Learner

> Transform your learning experience with AI-powered video summaries and intelligent content organization

[![Status](https://img.shields.io/badge/Status-MVP-orange)](https://github.com/yourusername/fast-learner)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/Version-1.0.0-green.svg)](https://github.com/yourusername/fast-learner/releases)

## ✨ What is Fast Learner?

Fast Learner is an intelligent study companion that revolutionizes how you consume educational content. By leveraging advanced AI models, it transforms lengthy YouTube videos into concise, actionable summaries, helping you learn faster and retain more.

## 🎯 Key Features

### 🧠 **AI-Powered Summaries**
- Generate intelligent summaries using state-of-the-art LLM models
- Multiple summary types: Brief, Detailed, Key Points
- Automatic transcription and content analysis

### 📺 **Smart Video Management**
- Organize YouTube educational content effortlessly
- Track learning progress across videos
- Categorize content by subject or difficulty

### ⭐ **Community Reviews**
- Rate and review educational content
- Share feedback with the learning community
- Discover highly-rated educational resources

### 👨‍🏫 **Creator Insights**
- Follow your favorite educational channels
- Track creator statistics and content quality
- Discover new educators in your field

### 📊 **Learning Analytics**
- Monitor your learning patterns and progress
- Track time saved through AI summaries
- Identify your most effective learning sources

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- Node.js 18+ (for frontend)
- Database (PostgreSQL/MySQL)
- YouTube API key
- OpenAI/Anthropic API key

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/fast-learner.git
cd fast-learner

# Install Python dependencies
pip install -r requirements.txt

# Install frontend dependencies
cd frontend
npm install
cd ..

# Set up environment variables
cp .env.example .env
# Edit .env with your API keys and database credentials

# Run database migrations
python manage.py migrate

# Start the backend server
python app.py

# In a new terminal, start the frontend
cd frontend
npm run dev
```

### First Steps

1. **Create Account** - Sign up and set your learning preferences
2. **Add Content** - Paste YouTube URLs of educational videos
3. **Generate Summaries** - Let AI create intelligent summaries
4. **Review & Rate** - Help the community by rating content quality
5. **Track Progress** - Monitor your learning journey

## 🏗️ Architecture

### Database Schema
Our robust data model supports comprehensive learning management:

- **Users** - Account management and preferences
- **Videos** - YouTube content metadata and status
- **Summaries** - AI-generated content with multiple formats
- **Model_LLM** - AI model configurations and settings
- **Reviews** - Community ratings and feedback system
- **Creators** - Educational channel tracking
- **Video_Clicks** - Usage analytics and engagement metrics

## 🛠️ Technology Stack

- **Backend**: Python Flask, SQLAlchemy
- **Database**: PostgreSQL with SQLAlchemy ORM
- **AI Integration**: OpenAI GPT-4, Anthropic Claude
- **Frontend**: React, TypeScript, Tailwind CSS
- **Video Processing**: YouTube API, Python libraries (youtube-dl, moviepy)
- **Authentication**: Flask-JWT-Extended, bcrypt

## 📈 Roadmap

### Phase 1 (Current - MVP)
- [x] Basic video import and summarization
- [x] User authentication and profiles
- [x] Simple review system
- [ ] Mobile-responsive design

### Phase 2 (Next Release)
- [ ] Advanced summary customization
- [ ] Collaborative learning features
- [ ] Integration with popular note-taking apps
- [ ] Offline summary access

### Phase 3 (Future)
- [ ] AI-powered quiz generation
- [ ] Learning path recommendations
- [ ] Multi-language support
- [ ] Browser extension

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

### Development Setup

```bash
# Fork the repository
# Clone your fork
git clone https://github.com/yourusername/fast-learner.git

# Set up Python virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install Python dependencies
pip install -r requirements.txt

# Install frontend dependencies
cd frontend
npm install
cd ..

# Create a feature branch
git checkout -b feature/amazing-feature

# Make your changes and commit
git commit -m 'Add amazing feature'

# Push to your fork
git push origin feature/amazing-feature

# Create a Pull Request
```

## ⚖️ Legal & Responsible Use

**Important Notice**: Fast Learner is designed exclusively for educational content that you have legal access to, including:
- University lectures and courses
- Educational webinars and tutorials  
- Open-source learning materials
- Personal educational content

**We strictly prohibit**:
- Downloading copyrighted content without permission
- Redistributing protected educational materials
- Commercial use of copyrighted summaries

By using Fast Learner, you agree to respect all copyright laws and terms of service of content platforms.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- OpenAI & Gemini for providing powerful language models
- YouTube for their comprehensive API
- The open-source community for invaluable tools and libraries
- Educators worldwide who make learning accessible

## 📞 Support

- 📧 Email: support@fastlearner.dev
- 🐛 Issues: [GitHub Issues](https://github.com/yourusername/fast-learner/issues)
- 💬 Discord: [Join our community](https://discord.gg/fastlearner)
- 📖 Documentation: [docs.fastlearner.dev](https://docs.fastlearner.dev)

---

<div align="center">
  <p><strong>Made with ❤️ for learners everywhere</strong></p>
  <p>⭐ Star us on GitHub if Fast Learner helps accelerate your learning journey!</p>
</div>