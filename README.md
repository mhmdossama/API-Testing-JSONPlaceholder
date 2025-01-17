# API Testing with JSONPlaceholder

This repository contains my practice work on testing APIs using the [JSONPlaceholder](https://jsonplaceholder.typicode.com/) service. The tests were written and executed using Postman and Newman.

## Contents

- **Postman Collections**: Two collections are provided, one with tests and one without.
- **Newman Report**: An HTML report generated by Newman.
- **Bug Report Example**: A sample bug report based on the testing results.

## Postman Collections

- `main-collection.json`: This collection includes tests for various API endpoints with variables, chaining, pre-request and post-request scripts, and assertions.
- `Without Tests-collection.json`: This collection includes requests without any tests.

## Newman Report

The Newman HTML report provides a detailed overview of the tests executed, their status, and any errors encountered. The report can be found in the `newman_reports` folder.

## Bug Report Example

The bug report example describes an issue found during testing, including steps to reproduce, expected results, actual results, and any relevant screenshots or logs.

## Tools Used

- **Postman**: For creating and managing API requests.
- **Newman**: For running Postman collections from the command line and generating reports.

## Assumptions and Notes

- Variables are used extensively, and it is recommended to run the collection in its entirety.
- Chaining, pre-request, and post-request scripts are implemented to ensure data consistency and correct request flow.
- Some requirements, such as response times, were assumed where not explicitly stated.
- The detailed summary of test execution can be viewed in the `newman-run-report.html`.

## License

This project is licensed under the MIT License.
