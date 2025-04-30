# Autoply

An intelligent automated job application system that streamlines your job search process using AI-powered tools and automation.

## 📋 Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Requirements](#requirements)
- [Configuration](#configuration)
- [Usage](#usage)
- [Architecture](#architecture)
- [Contributing](#contributing)
- [License](#license)
- [Disclaimer](#disclaimer)

## ✨ Features

### Core Functionality
- **Automated Job Search**
  - Multi-platform job search integration
  - Custom search filters and criteria
  - Intelligent job matching based on your profile
  - Blacklist/whitelist company functionality

### Smart Application System
- **Automated Application Process**
  - One-click job applications
  - Smart form filling
  - Document management
  - Application tracking

### AI Integration
- **Resume Customization**
  - AI-powered resume tailoring
  - Keyword optimization
  - ATS compatibility checking
  - Cover letter generation

### Analytics & Tracking
- **Application Dashboard**
  - Real-time application status
  - Success rate analytics
  - Interview conversion tracking
  - Job market insights

### Security & Privacy
- **Data Protection**
  - Secure credential storage
  - Privacy-first design
  - Compliance with platform ToS
  - Data encryption

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/autoply.git
cd autoply
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Install Chrome Browser and ChromeDriver:
```bash
# Windows (using setup script)
./setup/windows-setup.bat

# Linux/Mac
# Instructions coming soon
```

## 📋 Requirements

### System Requirements
- Python 3.10 or higher
- Google Chrome Browser
- 4GB RAM minimum(Recommended)
- Stable internet connection

### Python Dependencies
- Selenium WebDriver
- OpenAI API (optional)
- PyAutoGUI
- Streamlit (for dashboard)
- Additional requirements listed in requirements.txt

## ⚙️ Configuration

### Core Configuration Files
1. **config/personals.py**
   - Personal information
   - Contact details
   - Professional background

2. **config/search.py**
   - Job search preferences
   - Industry filters
   - Location settings
   - Experience level filters

3. **config/settings.py**
   - Application behavior
   - Automation settings
   - Security preferences
   - API configurations

4. **config/credentials.py**
   - API keys
   - Platform credentials
   - OAuth settings

## 🚀 Usage

### Basic Usage
```bash
python run.py
```

### Advanced Options
```bash
python run.py --headless  # Run in background
python run.py --debug     # Enable debug logging
python run.py --config custom_config.yaml  # Use custom config
```

### Dashboard Access
```bash
streamlit run dashboard.py
```

## 🏗️ Architecture

### Project Structure
```
autoply/
├── app/
│   ├── core/          # Core application logic
│   ├── ui/            # User interface components
│   └── utils/         # Utility functions
├── config/            # Configuration files
├── modules/           # Feature modules
│   ├── ai/           # AI components
│   ├── automation/    # Automation tools
│   └── analytics/     # Analytics engine
└── tests/            # Test suite
```

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Submit a pull request

Please read CONTRIBUTING.md for detailed guidelines.

## 📜 License

This project is licensed under the GNU Affero General Public License v3.0 (AGPLv3). See the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

This software is provided for educational purposes only. Users must:
- Comply with all platform terms of service
- Respect rate limits and robot policies
- Use the tool responsibly and ethically
- Be aware of and follow local laws and regulations

## 📞 Support

- GitHub Issues: For bug reports and feature requests

## 🙏 Acknowledgments

Special thanks to:
- Contributors and maintainers
- Open source community
- Testing and feedback providers

---

Made with ❤️ by Abhirup Karmakar, Mohammed Afaan, Jaydeep Das 
