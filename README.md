# LLM Code Conversion

A versatile framework for automated code conversion using Large Language Models (LLMs). While this implementation demonstrates Ab Initio XFR to PySpark conversion, the framework is designed to handle various code conversion scenarios:

- Legacy code modernization (COBOL → Java, Mainframe → Cloud)
- Cross-language migration (Java → Python, C++ → Rust)
- Enterprise application modernization (Monolith → Microservices)
- Domain-specific language transformation (SQL → SparkSQL, ETL → DataFlow)
- Framework migrations (Spring → Quarkus, Angular.js → React)

This repository containsa collection of notebooks and tools for converting Ab Initio XFR code to PySpark using Large Language Models (LLMs). The project demonstrates code conversion capabilities across different innovations including **Azure OpenAI, Azure AI Foundry Agents, and Microsoft Fabric**.

## Repository Structure

### 1. AI Foundry Agents Code Conversion Validation
Location: `/ai-foundry-agents-code-coversion-validation`

Contains:
- `xfr_to_pyspark_conversion_agent.ipynb`: Implements an Azure AI Foundry code interpreter agent that converts Ab Initio XFR logic to PySpark code. The agent:
  - Parses XFR artifacts and schemas
  - Generates PySpark transformation code
  - Validates the generated code using Pandas
  - Outputs fully validated PySpark scripts

### 2. LLMs Code Conversion Validation
Location: `/llms-code-conversion-validation`

Contains:
- `code_conversion.ipynb`: Implements an Azure OpenAI service-based code conversion that:
  - Reads XFR files and schema layouts
  - Generates PySpark transformation code
  - Performs code review and optimization
  - Outputs production-ready PySpark code

### 3. Microsoft Fabric Notebook
Location: `/microsoft-fabric-notebook`

Contains:
- `code_conversion-msft-fabric.ipynb`: Tailored implementation for Microsoft Fabric that:
  - Utilizes Fabric-specific features and optimizations
  - Provides seamless integration with OneLake storage
  - Includes Fabric-specific deployment considerations

## Features

- **Multi-Environment Support**: Solutions for Azure AI Foundry, Azure OpenAI, and Microsoft Fabric
- **Automated Code Conversion**: Convert Ab Initio XFR to PySpark automatically
- **Code Validation**: Built-in validation of generated code
- **Best Practices**: Implements PySpark best practices and optimizations
- **Documentation**: Detailed inline comments and explanations
- **Extensible Framework**: 
  - 🔄 **Adaptable for any source and target programming languages**
  - 🎯 **Customizable validation rules for different languages**
  - 🧩 **Modular design for adding new conversion patterns**
  - 📚 **Reusable components for various migration scenarios**

## Getting Started

1. Ensure you have the required environment variables set up in `.env` file:
   - Azure OpenAI Configuration
   - Azure AI Foundry Project Configuration
   - Azure AI Search Configuration (if needed)
   - Project-specific settings

2. Choose the appropriate notebook based on your environment:
   - For Azure AI Foundry: Use `xfr_to_pyspark_conversion_agent.ipynb`
   - For Azure OpenAI: Use `code_conversion.ipynb`
   - For Microsoft Fabric: Use `code_conversion-msft-fabric.ipynb`

3. Follow the notebook instructions for:
   - Setting up dependencies
   - Loading input files
   - Running the conversion
   - Validating results

## Requirements

- Python 3.x
- Azure OpenAI access
- Azure AI Foundry project setup (for AI Foundry implementation)
- Microsoft Fabric workspace (for Fabric implementation)
- Required Python packages (listed in notebooks)

## Contributing

Please read our contributing guidelines and code of conduct before submitting pull requests.

## License

See the LICENSE file for details.
