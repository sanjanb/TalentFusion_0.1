# TalentFusion

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) TalentFusion is an AI-powered skill matcher platform designed to bridge the gap between talented individuals and ideal career opportunities. It leverages advanced machine learning techniques to analyze skills, generate personalized portfolios, and provide actionable insights for career growth.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Technology Stack](#technology-stack)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **AI-Powered Skill Analysis:** Deep learning models analyze resumes and profiles to extract and understand relevant skills.
- **Automated Portfolio Generation:** Creates personalized digital portfolios showcasing skills, projects, and experience.
- **Skill Gap Analysis:** Identifies skill gaps by comparing user skills with industry demands and provides personalized learning recommendations.
- **Personalized Job Recommendations:** Matches users with ideal job opportunities based on their skills and preferences.
- **Skill Assessments:** Integrated AI-powered coding tests and project reviews.
- **Recruiter Smart-Match System:** Efficient candidate matching and ranking for recruiters.
- **User-Friendly Dashboard:** Clear and intuitive interface for managing skills, portfolios, and job applications.
- **Comprehensive Portfolio Page:** A page displaying all the user's skills, projects, experience, education, and certifications.
- **Skill Analysis Page:** A page detailing a user's skills, skill gaps, and learning recommendations.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.x
- Node.js and npm
- PostgreSQL (or firebase account)
- Git

### Installation

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/sanjanb/TalentFusion_0.1.git](https://www.google.com/search?q=https://github.com/sanjanb/TalentFusion_0.1.git)
    cd TalentFusion_0.1
    ```

2.  **Backend Setup (Flask):**

    ```bash
    cd backend
    python -m venv venv
    source venv/bin/activate  # On macOS/Linux
    venv\Scripts\activate  # On Windows
    pip install -r requirements.txt
    # Configure Supabase credentials and database settings.
    # Run the Flask application
    python app.py
    ```

3.  **Frontend Setup (React):**

    ```bash
    cd ../frontend
    npm install
    # Configure Supabase client credentials in React.
    npm start
    ```

## Usage

1.  **Sign up or log in:** Create an account or log in to access the platform.
2.  **Upload your resume or connect your LinkedIn profile:** Allow the AI to analyze your skills.
3.  **Explore personalized job recommendations:** Browse and apply for relevant job opportunities.
4.  **View and edit your portfolio:** Customize your digital portfolio.
5.  **Analyze your skill gaps:** Identify areas for improvement and access personalized learning recommendations.
6.  **Take skill assessments:** Test and showcase your skills.

## Technology Stack

- **Backend:** Flask (Python)
- **Frontend:** React
- **Database:** PostgreSQL (firebase)
- **AI Models:**
  - CNN & NLP for resume analysis
  - GPT for portfolio generation
  - Collaborative Filtering & Deep Learning for job recommendations
  - TF-IDF and Cosine Similarity for content analysis.
  - SpaCy for NER.
- **Libraries:** PyMuPDF, BeautifulSoup, Scikit-learn, TensorFlow/PyTorch, OpenAI API, Axios, etc.

## Contributing

Contributions are welcome! Please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them.
4.  Push your changes to your fork.
5.  Submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

- [Your Name/Organization]
- [Your Email]
- [GitHub Repository](https://github.com/sanjanb/TalentFusion_0.1)
