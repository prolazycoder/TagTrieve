# TagTrieve

## 📌 Overview

This web application automates the process of extracting relevant job posts from LinkedIn and generating personalized emails for outreach. Using advanced web scraping and AI-driven text generation, it helps users craft cold emails, follow-ups, networking emails, and thank-you emails based on job post keywords. Users also have the flexibility to review and modify emails before sending.

## 🚀 Features

- Extracts **relevant job posts** from LinkedIn using web scraping.
- Searches for **email IDs** in job posts for targeted outreach.
- **Generates AI-powered emails** (cold emails, follow-ups, networking, and thank-you emails) using OpenAI API.
- Personalizes emails by incorporating **relevant keywords from job posts**.
- Allows users to **review and edit** emails before sending.
- **Secure authentication** with LinkedIn OAuth.
- Implements **encryption techniques** to protect user data.

## 🛠️ Tech Stack

- **Frontend:** React
- **Backend:** Node.js
- **Scraper:** BeautifulSoup, Playwright
- **AI:** OpenAI API
- **Authentication:** LinkedIn OAuth
- **Security:** Encryption methods for user data

## 📦 Installation

### Prerequisites

Ensure you have the following installed:

- **Node.js** (v16 or later)
- **Python** (for BeautifulSoup and Playwright)
- **npm** or **yarn**

### Clone the Repository

```bash
git clone https://github.com/your-username/linkedin-scraper-email-generator.git
cd linkedin-scraper-email-generator
```

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables in a `.env` file:
   ```plaintext
   LINKEDIN_OAUTH_CLIENT_ID=your_client_id
   LINKEDIN_OAUTH_CLIENT_SECRET=your_client_secret
   OPENAI_API_KEY=your_openai_api_key
   ```
4. Start the backend server:
   ```bash
   npm start
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend server:
   ```bash
   npm start
   ```

## 🛡️ Security & Privacy

- Uses **LinkedIn OAuth** for authentication to ensure secure login.
- **Encrypts user information** to prevent data leaks.
- Complies with **LinkedIn’s policies** to avoid account bans.

## 🏗️ Usage

1. **Login with LinkedIn OAuth** to authenticate securely.
2. **Enter job keywords** to filter and extract relevant job posts.
3. **Automatically generate emails** using AI-powered keyword extraction.
4. **Edit and customize** the generated email before sending.
5. **Securely manage data**, ensuring privacy and compliance.

## 🔮 Future Improvements

- **Automated job tracking**: Monitor job posts for updates and new openings.
- **Multiple email templates**: Customize emails for different outreach strategies.
- **AI-powered reply suggestions**: Generate responses based on recruiter messages.
- **Improved anti-detection techniques**: Reduce chances of LinkedIn scraping restrictions.
- **Integration with email services**: Automate email sending via SMTP or third-party APIs.

---


