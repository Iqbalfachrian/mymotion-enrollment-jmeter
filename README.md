# Batch Enrollment API Performance Testing with Apache JMeter

## Scope

A sanitized JMeter portfolio project demonstrating API testing for a batch-enrollment workflow.

## Scenario

- 1 virtual user
- 1 synthetic enrollment chunk for the portfolio demo
- CSV-driven payload selection
- Dynamic session handling
- JSON extraction and response assertions
- Batch-status polling

The original internal test model used 40 chunks of 250 synthetic participants. The raw 10,000-record payloads are intentionally excluded from this portfolio copy.

## JMeter Components

- HTTP Request
- HTTP Header Manager
- HTTP Cookie Manager
- CSV Data Set Config
- JSON Extractor
- JSON Assertion
- While Controller
- Loop Controller
- Constant Timer

## Security and Reproducibility

- No real credentials, cookies, JWTs, or authorization headers are committed.
- Test data is synthetic.
- Local credentials must be supplied through an ignored properties file or command-line properties.
- The included JMX uses a placeholder host and is not intended to call an internal environment as-is.


