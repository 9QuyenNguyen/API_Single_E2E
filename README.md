# REST API Testing Project
A comprehensive Postman collection for testing the **Restful Booker API** (https://restful-booker.herokuapp.com). This project includes automated API tests with pre-request scripts, test assertions, and detailed HTML reporting.

## Overview
This API testing project validates the booking system endpoints of the Restful Booker API, including:

- **Single API Tests**: Individual endpoint validations with comprehensive assertions
- **Booking Creation**: Tests for creating booking records with valid data
- **Type Validation**: Ensures response fields return correct data types
- **Response Time Monitoring**: Validates API response times are within acceptable limits
- **Request-Response Matching**: Verifies sent request data matches the API response

## Project Structure

- **API_Demo.postman_collection.json**: Complete Postman collection with API requests, pre-request scripts, and test assertions.
- **REST_API.postman_environment.json**: Environment configuration with base URL for the Restful Booker API.
- **report_REST_API.html**: HTML test execution report with results and metrics.

## Prerequisites
To use this project, ensure you have the following installed:

- [Postman](https://www.postman.com/downloads/)
- Internet connection (for accessing the Restful Booker API)
- Web browser (to view the HTML report)

## Setup Instructions
1. **Import the Collection**:
   - Open Postman
   - Click "Import" → Select `API_Demo.postman_collection.json`

2. **Import the Environment**:
   - Click "Environments" (left sidebar)
   - Click "Import" → Select `REST_API.postman_environment.json`

3. **Select the Environment**:
   - In the top-right corner of Postman, select the "REST_API" environment

## Running Tests

### Run Individual Requests
- Navigate to "Single_API" folder in the collection
- Select any request (e.g., "CreateBooking API - Valid")
- Click "Send" to execute

### Run Full Collection
- Right-click on the collection name → "Run collection"
- The collection runner will execute all requests sequentially
- A report will be generated with test results

## Viewing Results
After running the collection:
1. Check the Postman test results in the "Test Results" tab
2. Open `report_REST_API.html` in a web browser for a detailed HTML report
3. Review response times, assertions passed/failed, and request/response details

## Notes
- Ensure the API server is running and accessible before executing the collection.
- Update the collection and environment files as needed to match your API endpoints and test scenarios.
