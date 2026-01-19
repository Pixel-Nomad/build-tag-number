# 🧠 GitHub Action for Build Number Management
The GitHub Action for Build Number Management is a powerful tool designed to generate and manage build numbers for workflow runs. This action provides a seamless way to track and automate build numbers, making it easier to manage and monitor your GitHub workflows. The core feature of this project is its ability to interact with the GitHub API, read and write files, and set environment variables, all of which are crucial for build number management.

## 🚀 Features
- **Automated Build Number Generation**: The action automatically generates build numbers based on the workflow run, ensuring that each build is uniquely identified.
- **Build Number Storage**: The action stores the generated build number in a file, allowing for easy retrieval and use in subsequent workflow steps.
- **Environment Variable Setup**: The action sets the build number as an environment variable, making it accessible to other parts of the workflow.
- **Error Handling**: The action includes robust error handling, logging error messages and exiting the process when necessary to ensure that workflow runs are not compromised by build number management issues.
- **GitHub API Interaction**: The action sends requests to the GitHub API with authentication, handling responses and parsing JSON data to manage build numbers and tags effectively.

## 🛠️ Tech Stack
- **Node.js**: The runtime environment for the GitHub Action, utilizing Node.js version 20 for execution.
- **GitHub API**: The action interacts with the GitHub API to manage build numbers and tags, leveraging the API's capabilities for workflow automation.
- **HTTPS**: The action uses HTTPS for making requests to the GitHub API, ensuring secure communication.
- **Zlib**: The action utilizes zlib for handling gzip compression and decompression, optimizing data transfer.
- **FS**: The action interacts with the file system using the fs module, reading and writing files to store and retrieve build numbers.

## 📦 Installation
To use this GitHub Action, you'll need to have a GitHub repository set up with a workflow file (.yml) that includes the action. Here are the steps to get started:
1. **Create a Workflow File**: In your repository, create a new file in the `.github/workflows` directory, e.g., `.github/workflows/build-number-management.yml`.
2. **Specify the Action**: In the workflow file, specify the GitHub Action for Build Number Management, including any required inputs such as a GitHub token.
3. **Commit and Push**: Commit the changes to your repository and push them to GitHub to trigger the workflow.

## 💻 Usage
The GitHub Action for Build Number Management is designed to be used within a GitHub workflow. Once the action is specified in your workflow file, it will automatically generate and manage build numbers for each workflow run. You can access the build number as an output of the action or as an environment variable in subsequent steps of your workflow.

## 📂 Project Structure
```markdown
.
├── action.yml
├── main.js
├── node_modules
│   ├── https
│   ├── zlib
│   └── fs
├── package.json
└── README.md
```

## 📸 Screenshots

## 🤝 Contributing
Contributions are welcome and appreciated. If you find an issue or have a feature request, please open an issue or submit a pull request.

## 📝 License
This project is licensed under the MIT License.

## 📬 Contact
For questions, suggestions, or concerns, please contact us at [support@example.com](mailto:support@example.com).

## 💖 Thanks Message
A huge thank you to all contributors and users of this project. Your support and feedback are invaluable.

This is written by [readme.ai](https://readme-generator-phi.vercel.app/)
