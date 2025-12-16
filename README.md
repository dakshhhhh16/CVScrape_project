# CVScrape 📄

> Scrape your LinkedIn profile and generate an ATS-friendly resume powered by AI

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)

## ✨ Features

-  **Get Noticed by Recruiters** - Stand out with a professionally structured resume
-  **AI-Powered Resume** - Leverage AI to optimize your resume content
-  **Quick and Easy** - Generate your resume in minutes
-  **ATS Ready** - Formatted to pass Applicant Tracking Systems

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- A [Proxycurl](https://nubela.co/proxycurl) API key

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/daksh-pathak/CVScrape.git
   cd CVScrape
   ```

2. Install dependencies:
   ```bash
   pip install requests python-dotenv
   ```

3. Create a `.env` file in the project root:
   ```
   API_KEY=your_proxycurl_api_key_here
   ```

4. Update the LinkedIn URL in `main.py` to your profile

### Usage

Run the script to fetch your LinkedIn profile data:

```bash
python main.py
```

This will save your profile data to `profile_data.json`.

## 📁 Project Structure

```
CVScrape/
├── main.py              # Main script to fetch LinkedIn data
├── profile_data.json    # Output file with scraped profile data
├── .env                 # Environment variables (API key)
└── README.md
```

## 🔧 Configuration

Edit the `main.py` file to customize:

- `linkedin_profile_url` - Your LinkedIn profile URL
- API parameters for additional data (skills, salary estimates, etc.)

## 📄 License

This project is licensed under the GPL-3.0 License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Daksh Pathak**

- LinkedIn: [@daksh-pathak-1855811b1](https://www.linkedin.com/in/daksh-pathak-1855811b1/)
