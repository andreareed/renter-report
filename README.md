# Renter Report

## Getting Started

A valid `common.env` file is necessary to get started. Modify `common.template.env` to include the necessary credentials, and then rename the file to `common.env`.

Once the credentials are in place, run `docker-compose up` from within the directory to start the project.

Navigate to `https://localhost.com:3000` to see your app in the browser.

## Running API Tests

This project includes [Hapi Lab](https://hapi.dev/module/lab/) injection testing for testing API endpoints. To run the test suite, use `docker-compose exec api npm run test`. These tests have also been configured to run in CircleCI if enabled.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
