# Postman Tests for GitHub API

This repository contains a collection of Postman tests for various GitHub API endpoints. These tests can be used to interact with GitHub's API and perform actions such as retrieving user information, creating repositories, managing files, and more. The tests are organized into folders based on the API endpoints they target.

## Getting Started

To get started with these tests, follow the steps below:

1. Install Postman: If you haven't already, download and install [Postman](https://www.postman.com/downloads/).

2. Import the Collection: In Postman, click on the **Import** button and select the `github-api-tests.postman_collection.json` file from this repository.

3. Set Environment Variables: Before running the tests, make sure to set the necessary environment variables such as `base_url`, `access_token`, and any other variables required for authentication.

4. Run the Tests: Once the environment variables are set, you can run the tests by selecting the desired request and clicking on the **Send** button.

## List of Available Tests

### Home Page
- **GET** - Retrieve the home page of GitHub.

### User Info
- **GET** - Get information about a specific user.

### List of Repositories
- **GET** - Retrieve a list of repositories for a user.

### Create Repository
- **POST** - Create a new repository.

### Add Simple File
- **PUT** - Add a simple file to a repository.

### Update Repository
- **PATCH** - Update a repository.

### File Info
- **GET** - Get information about a specific file.

### Delete File
- **DELETE** - Delete a file from a repository.

### Update Repository 1.0
- **PATCH** - Update a repository to version 1.0.

### Delete Repository
- **DELETE** - Delete a repository.

Please note that these tests assume you have a valid access token with the necessary permissions to perform the respective actions on the GitHub API.

## Contributing

If you would like to contribute to this collection of tests, feel free to submit a pull request with your changes. Contributions are always welcome!

## License

This repository is licensed under the [MIT License](LICENSE). Feel free to use and modify the tests as per your needs.
