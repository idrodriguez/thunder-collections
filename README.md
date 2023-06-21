# Thunder Collections for API Testing

This repository contains a collection of Thunder collections that can be used
with Thunder Client, an open-source alternative to Postman, for testing various
APIs. These collections are designed to simplify daily requests and provide
pre-defined requests for specific APIs.

## Collections

- [thunder-collection_JIRA Cloud API.json](./thunder-collection_JIRA%20Cloud%20API.json):
  Contains requests to the JIRA Cloud API, providing information about issues,
  custom fields, and versions.

- [thunder-collection_Snyk API.json](./thunder-collection_Snyk%20API.json):
  Contains requests to the Snyk API, allowing you to retrieve security
  vulnerabilities found during scans for repositories or Docker images.

- [thunder-collection_SonarCloud API.json](./thunder-collection_SonarCloud%20API.json):
  Contains requests to the SonarCloud API, enabling you to interact with quality
  gates and access metrics such as code coverage or complexity for repositories.

- [thunder-collection_GitHub API.json](./thunder-collection_GitHub%20API.json) :
  Contains requests to the GitHub API, enabling you to get information like
  repositories, pull-requests and commits.

## Getting Started

To use these collections, follow the steps below:

1. Install [Visual Studio Code](https://code.visualstudio.com/) if you haven't
   already.

2. Install the
   [Thunder Client extension](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client)
   in Visual Studio Code.

3. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/idrodriguez/thunder-collections.git
   ```

4. Open Visual Studio Code and navigate to the "Collections" tab in Thunder
   Client.

5. Import the desired collection from the repository by clicking on the "Import
   Collection" button and selecting the corresponding JSON file.

6. Set up the environment for each collection by defining the base URL and any
   required authentication or default values as environment variables.

7. You're all set! You can now explore the imported collection and execute the
   requests using Thunder Client.
