# Purple BlazorWASM

This project demonstrates the creation, development, and deployment of a Blazor WebAssembly (WASM) application using .NET 8. It adheres to SOLID principles to ensure a clean, maintainable codebase, and is deployed as an Azure Static Website for global accessibility.

## Prerequisites

Before you begin, ensure you have the following installed:
- [.NET 8 SDK](https://dotnet.microsoft.com/download)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later with the ASP.NET and web development workload
- [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)
- An active Azure subscription

## Getting Started

### Step 1: Create the Project

1. Open your terminal or command prompt.
2. Navigate to the directory where you want to create the project.
3. Run the following command to create a new Blazor WebAssembly project:

   dotnet new blazorwasm -o src/Client --force

4. Navigate into your project directory:

   cd src/Client


5. Open the project in Visual Studio or your preferred IDE.

### Step 2: Add Assets

1. Place any required assets (images, CSS, JavaScript files) in the `wwwroot` folder of your project.

### Step 3: Apply SOLID Principles

Ensure your project adheres to SOLID principles for better maintainability and scalability. Here are some general guidelines:

- **Single Responsibility Principle**: Keep components focused on a single task.
- **Open/Closed Principle**: Design components to be open for extension but closed for modification.
- **Liskov Substitution Principle**: Derived classes must be substitutable for their base classes.
- **Interface Segregation Principle**: Use many client-specific interfaces instead of one general-purpose interface.
- **Dependency Inversion Principle**: Depend on abstractions, not on concretions.

Refactor your code accordingly to follow these principles.

### Step 4: Deploy to Azure Static Web Apps

1. Commit your changes and push them to your GitHub repository.
2. In the Azure Portal, create a new Static Web App.
3. Follow the wizard to connect your GitHub repository and configure the build and deployment settings.
4. Once the deployment is complete, Azure will provide you with a URL to access your Blazor WASM application.

## Contributing

Contributions are welcome! Please read our [Contributing Guide](CONTRIBUTING.md) for more information.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
