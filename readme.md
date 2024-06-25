# Gemini Pro LLM Streamlit Apps

Welcome to the **Gemini LLM & Pro Streamlit Apps** repository! This project contains two distinct Streamlit applications. The first app leverages the Gemini LLM to respond to user queries, while the second app uses Gemini Pro to analyze resume PDFs and match them with job descriptions, highlighting missing keywords and providing a conclusion about the resume.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
  - [Gemini LLM Query Response App](#gemini-llm-query-response-app)
  - [Gemini Pro Resume Matcher App](#gemini-pro-resume-matcher-app)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This repository houses two Streamlit applications:

1. **Gemini LLM Query Response App**: This app uses the Gemini Large Language Model (LLM) to respond to user queries with accurate and relevant answers.
2. **Gemini Pro Resume Matcher App**: This app takes resume PDFs and matches them with job descriptions, identifying missing keywords and providing a summary of the resume's suitability for the job.

## Features

- **Gemini LLM Query Response App**
  - Leverages advanced language model capabilities.
  - Provides accurate and contextually relevant responses to user queries.

- **Gemini Pro Resume Matcher App**
  - Analyzes resumes in PDF format.
  - Compares resumes against job descriptions.
  - Highlights missing keywords.
  - Provides a conclusion about the resume's match with the job description.

## Installation

To run these applications locally, follow these steps:

1. Clone this repository:
   \`\`\`bash
   git clone https://github.com/yourusername/gemini-llm-pro-streamlit-apps.git
   cd gemini-llm-pro-streamlit-apps
   \`\`\`

2. Create and activate a virtual environment (optional but recommended):
   \`\`\`bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use \`venv\\Scripts\\activate\`
   \`\`\`

3. Install the required dependencies:
   \`\`\`bash
   pip install -r requirements.txt
   \`\`\`

## Usage

### Gemini LLM Query Response App

To run the Gemini LLM Query Response App, execute the following command:

\`\`\`bash
streamlit run gemini_llm_query_app.py
\`\`\`

This will start a local Streamlit server, and you can interact with the app through your web browser.

### Gemini Pro Resume Matcher App

To run the Gemini Pro Resume Matcher App, execute the following command:

\`\`\`bash
streamlit run gemini_pro_resume_matcher_app.py
\`\`\`

This will start a local Streamlit server, and you can interact with the app through your web browser.

## Contributing

We welcome contributions to enhance these applications! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request. Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (\`git checkout -b feature-branch\`).
3. Make your changes.
4. Commit your changes (\`git commit -m 'Add some feature'\`).
5. Push to the branch (\`git push origin feature-branch\`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

We hope you find these applications useful! If you have any questions or need further assistance, please feel free to contact us. Happy coding!
