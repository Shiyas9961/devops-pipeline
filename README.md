# CI/CD Pipeline with GitHub Actions

This project demonstrates a simple yet effective CI/CD pipeline using GitHub Actions. The pipeline automates the build and test process for a Node.js application.

## 🚀 Features

- **Automated Testing**: Runs tests on every push to the main branch
- **Node.js Environment**: Uses Node.js 18 for consistent builds
- **Dependency Management**: Automatically installs project dependencies
- **Workflow Status**: Badge showing the build status of the main branch

## 🛠️ Pipeline Workflow

The CI/CD pipeline is defined in `.github/workflows/pipeline.yaml` and includes the following steps:

1. **Checkout Code**: Fetches the latest code from the repository
2. **Setup Node.js**: Configures Node.js 18 environment
3. **Install Dependencies**: Runs `npm install` to install all required packages
4. **Run Tests**: Executes tests using `npm test`

## 🔧 Prerequisites

- GitHub account
- Node.js 18 or later
- npm (comes with Node.js)

## 🚦 Getting Started

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-name>
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run tests locally:
   ```bash
   npm test
   ```

## 🤖 GitHub Actions

The pipeline automatically triggers on every push to the `main` branch. You can monitor the workflow runs in the `Actions` tab of your GitHub repository.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
