/**
 * @file README.md
 *
 * @brief Readme file for the Car Maintenance Console Application.
 */

## Overview
The Car Maintenance Console Application is a user-friendly tool that helps users manage and maintain records of vehicle service history, maintenance reminders, expenses, and fuel efficiency reports. It also incorporates a robust User Authentication system to ensure data security.

---

## Functionalities

### Menu Options
Users can:
- **Register**: Add a new record.
- **Update**: Modify an existing record easily, regardless of the number of records.
- **Delete**: Remove specific entries or entire records as needed.
- **View**: Browse through records efficiently.

### Record Categories
The application organizes records into the following categories for clarity and ease of access:

#### 1. **Service History Tracking**
- Vehicle’s Model
- Vehicle’s Service Kilometer Reading
- Service Provider
- Service Cost

#### 2. **Maintenance Reminders**
- Vehicle’s Model
- Next Service Kilometer Reading
- Service Type

#### 3. **Expense Logging**
- Vehicle’s Model
- Expense Type
- Expense Date
- Cost

#### 4. **Fuel Efficiency Reports**
- Vehicle’s Model
- Fuel Consumption (L/100KM)

### User Authentication
Only authorized users with valid credentials (username and password) can access the system, ensuring secure management of sensitive records.

---

## Testing and Validation
The application has undergone rigorous testing to ensure reliability:
- **Testing Frameworks**: XUnit.
- **Coverage**: Achieves 100% test coverage with 100% success in unit tests.

---

### Releases
- [![GitHub release badge](https://badgen.net/github/release/ucoruh/vs-net-core-template)](https://github.com/ucoruh/vs-net-core-template/releases/latest)

### Platforms
- ![Ubuntu badge](assets/badge-ubuntu.svg)
- ![macOS badge](assets/badge-macos.svg)
- ![Windows badge](assets/badge-windows.svg)

### Test Coverage
[![.NET Windows + Doxygen + Test + Release](https://github.com/ucoruh/vs-net-core-template/actions/workflows/build_check_ubuntu_windows.yml/badge.svg)](https://github.com/ucoruh/vs-net-core-template/actions/workflows/build_check_ubuntu_windows.yml)

**Coverage Metrics:**
- **Overall**: ![All](assets/badge_combined.svg)
- **Branch Coverage**: ![Branch Coverage](assets/badge_branchcoverage.svg)
- **Line Coverage**: ![Line Coverage](assets/badge_linecoverage.svg)
- **Method Coverage**: ![Method Coverage](assets/badge_methodcoverage.svg)

### Features
This project template enables users to:
- Create and manage releases.
- Perform testing with coverage.
- Share documentation seamlessly using GitHub Actions.

---

## Environment Setup

### Prerequisites
Ensure you have the following installed:
- Visual Studio with .NET Core 7.0 and XUnit.
- Package managers: [Chocolatey](https://chocolatey.org/install) and [Scoop](https://scoop.sh/).

### Additional Tools
- **Astyle**: For pre-commit code formatting.
- **Doxygen and Graphviz**: For documentation generation.
- **MkDocs Material Theme**: For creating project websites.

### Setup Scripts
Scripts for installation and configuration are provided for:
1. **Astyle Installation**: Includes configuration for automatic code formatting.
2. **Doxygen Setup**: Includes default configuration generation and warnings setup.
3. **LCOV and Report Generator**: For HTML document and test report generation.

