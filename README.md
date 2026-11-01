# Nilkamal Selenium Automation Framework

A Java-based web UI automation framework built with Selenium WebDriver, TestNG, and the Page Object Model (POM). The project automates key user journeys on the Nilkamal Furniture website.

## Tech Stack

- Java
- Selenium WebDriver 4.21.0
- TestNG 7.10.2
- Maven
- Apache POI (Excel data handling)
- ExtentReports
- Page Object Model (POM)

## Features

- Page Object Model architecture
- Browser-based UI automation
- TestNG test execution and grouping
- Data-driven testing using Excel
- Reusable page and wait utilities
- Screenshot utilities
- ExtentReports test reporting
- End-to-end test scenarios

## Project Structure

```text
src/
├── main/
│   ├── java/
│   │   ├── base/
│   │   ├── config/
│   │   ├── pages/
│   │   └── utils/
│   └── resources/
│       └── ObjectRepo/
└── test/
    ├── java/
    │   ├── base/
    │   ├── listeners/
    │   └── tests/
    └── resources/
        └── testdata/

pom.xml
testng.xml
End-to-End.xml
