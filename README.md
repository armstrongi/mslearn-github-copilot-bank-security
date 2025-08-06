This project contains a C# banking application with security features and comprehensive unit testing. It's designed as a Microsoft Learn project for exploring GitHub Copilot capabilities in bank security scenarios.

## Project Structure

The project consists of two main projects:

### 1. BankAccountClass (BankAccountClass)
- **Main Project**: Contains the core banking logic
- **Key Files**:
  - `BankAccount.cs` - Core bank account implementation
  - `Program.cs` - Application entry point
  - `BankAccount.csproj` - Project configuration

### 2. BankAccount.UnitTests (BankAccount.UnitTests)
- **Test Project**: Comprehensive unit testing suite
- **Key Files**:
  - `BankAccountTests.cs` - Unit test implementations
  - `BankAccount.UnitTests.csproj` - Test project configuration

## Technology Stack

- **.NET 8.0**: Target framework for both projects
- **xUnit 2.5.3**: Unit testing framework
- **Coverlet**: Code coverage analysis
- **Microsoft Test Platform**: Test execution infrastructure

## Getting Started

### Prerequisites
- .NET 8.0 SDK installed
- Visual Studio Code or Visual Studio

### Building the Project
```bash
# Build the entire solution
dotnet build mslearn-github-copilot-bank-security.sln

# Or build individual projects
dotnet build BankAccountClass/BankAccount.csproj
dotnet build BankAccount.UnitTests/BankAccount.UnitTests.csproj
```

### Running the Application
```bash
cd BankAccountClass
dotnet run
```

### Running Tests
```bash
# Run all tests
dotnet test

# Run tests with coverage
dotnet test --collect:"XPlat Code Coverage"

# Run tests in specific project
dotnet test BankAccount.UnitTests/BankAccount.UnitTests.csproj
```

## Development Environment

This workspace is configured for development in:
- **Container Environment**: Ubuntu 24.04.2 LTS
- **IDE Support**: Optimized for Visual Studio Code
- **Package Management**: NuGet packages restored automatically

## Key Features

- **Security-focused banking operations**
- **Comprehensive test coverage**
- **Clean architecture with separation of concerns**
- **Modern .NET development practices**
- **Continuous integration ready**

## Project Configuration

The solution is configured with:
- Debug and Release build configurations
- Cross-platform compatibility
- Package references for testing frameworks
- Code coverage collection capabilities

## Learning Objectives

This workspace is designed to help developers:
- Explore secure banking application development
- Practice unit testing with xUnit
- Learn GitHub Copilot integration patterns
- Understand .NET security best practices

---

*This is a Microsoft Learn project focused on GitHub Copilot and banking security scenarios.*