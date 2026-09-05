# 🤖 GitHub Assistant

An AI-powered **GitHub Activity Assistant** that helps developers understand, analyze, and improve their GitHub activity using intelligent analytics and AI-generated insights.

## 🚀 About the Project

**GitHub Assistant** is a developer productivity platform that connects with GitHub and transforms your coding activity into meaningful insights.

Instead of simply showing commits and repositories, the assistant analyzes your GitHub activity and helps you understand your coding consistency, productivity, repositories, contribution patterns, and areas for improvement.

## ✨ Features

* 🔐 GitHub account integration
* 📊 GitHub activity dashboard
* 🔥 Contribution streak tracking
* 📈 Contribution and productivity analytics
* 💻 Repository activity analysis
* 📝 Commit activity tracking
* 🔀 Pull request and issue tracking
* 🧠 AI-powered GitHub Assistant
* 💡 Personalized productivity recommendations
* 🏆 Achievement system
* 📅 Daily and weekly activity summaries
* 🌐 Responsive design for desktop, tablet, and mobile
* 🎨 Modern developer-focused UI

## 🤖 AI Assistant

The built-in AI assistant can analyze GitHub activity and answer questions such as:

* How active was I this month?
* What is my most active repository?
* Which programming language do I use the most?
* How consistent are my contributions?
* How can I improve my GitHub profile?
* What should I work on next?
* Give me a summary of my recent activity.

The AI provides insights based on the user's GitHub activity rather than generic recommendations.

## 📊 Analytics

GitHub Assistant provides insights into:

* Contributions
* Commits
* Pull requests
* Issues
* Repository activity
* Programming languages
* Contribution streaks
* Coding consistency

### GitHub Health Score

The application can generate an application-specific **GitHub Health Score (0–100)** based on activity and consistency.

> Note: This is an application-generated metric and is not an official GitHub score.

## 🛠️ Technology Stack

### Frontend

* React
* TypeScript
* Tailwind CSS

### Backend

* Node.js
* API services

### APIs & AI

* GitHub API
* Claude API

### Tools

* Git
* GitHub
* Antigravity

## 📁 Project Structure

```text
github-assistant/
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── hooks/
│   ├── utils/
│   └── types/
├── public/
├── .env.example
├── .gitignore
├── package.json
└── README.md
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/kirubakar67-stack/assisant-github.git
```

Move into the project:

```bash
cd assisant-github
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Then open the local URL shown in your terminal.

## 🔑 Environment Variables

Create a `.env` file in the project root and add the required credentials.

Example:

```env
GITHUB_CLIENT_ID=your_github_client_id
GITHUB_CLIENT_SECRET=your_github_client_secret
CLAUDE_API_KEY=your_claude_api_key
```

### ⚠️ Security

Never commit your `.env` file to GitHub.

Make sure `.gitignore` contains:

```text
.env
.env.local
node_modules/
```

## 🔐 GitHub OAuth

To enable GitHub login:

1. Create a GitHub OAuth application.
2. Add the application's Client ID.
3. Add the Client Secret to your environment variables.
4. Configure the correct callback URL.
5. Restart the development server.

Never expose the GitHub Client Secret in frontend code.

## 🧠 Claude AI

The AI functionality uses Claude to analyze structured GitHub activity data and generate developer-focused insights.

GitHub authentication tokens should **never be sent to the AI model**.

Only the required activity and analytics data should be provided to the AI service.

## 📱 Responsive Design

GitHub Assistant is designed to work across:

* 💻 Desktop
* 🖥️ Laptop
* 📱 Mobile
* 📲 Tablet

## 🔮 Future Improvements

* 📌 Personalized coding goals
* 📊 Advanced developer analytics
* 📧 Weekly GitHub reports
* 🏅 More achievement levels
* 📈 Long-term productivity trends
* 👥 Team activity analytics
* 📄 AI-powered GitHub profile improvement
* 🚀 Deployment automation

## 🎯 Vision

The goal of GitHub Assistant is to make GitHub activity easier to understand and turn raw developer activity into **useful insights, actionable goals, and continuous improvement**.

## 👨‍💻 Developer

**Kirubakar**


## 📄 License

This project is intended for educational and development purposes. Add an appropriate open-source license if you plan to distribute the project publicly.
