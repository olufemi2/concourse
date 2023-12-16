# Hello World Canary Deployment

## Overview

This project demonstrates a basic "Hello World" HTML application with a canary deployment approach using Concourse CI.

## Project Structure

- **source-code:** Contains the source code of the "Hello World" HTML application.
- **canary-deployment:** Houses the configuration for canary deployments.

## Concourse Pipeline

The Concourse pipeline consists of two main jobs:
1. **build-and-deploy-canary:**
   - Triggers on changes to the source code or canary deployment repository.
   - Builds the HTML application and deploys it to a canary environment.

## Tasks

### Build Task (`source-code/ci/tasks/build.yml`)

This task builds the HTML application and produces artifacts for deployment.

### Deploy Task (`canary-deployment/ci/tasks/deploy.yml`)

This task deploys the built artifacts to a canary environment.

## Getting Started

1. Clone the repository.
2. Set up Concourse CI with the provided pipeline.
3. Update deployment configurations as needed.
4. Trigger the pipeline to build and deploy the "Hello World" HTML application to the canary environment.

## Contributing

Feel free to contribute by opening issues or pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
