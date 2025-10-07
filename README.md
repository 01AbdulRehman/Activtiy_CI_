# Node.js CI Project

This project is a simple Node.js application that demonstrates how to set up a Continuous Integration (CI) pipeline using GitHub Actions and Jest for testing.

## Getting Started

To get started with this project, follow the instructions below.

### Prerequisites

Make sure you have Node.js and npm installed on your machine. You can download them from [nodejs.org](https://nodejs.org/).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/nodejs-ci-project.git
   cd nodejs-ci-project
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

### Running the Application

You can run the application by executing the following command:
```bash
node src/sum.js
```

### Running Tests

To run the tests, use the following command:
```bash
npm test
```

### CI Workflow

This project includes a CI workflow defined in `.github/workflows/ci.yml`. The workflow will automatically run tests on every push and pull request to the repository.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.