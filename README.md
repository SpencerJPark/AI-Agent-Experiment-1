# README

## AI Assistant for Data Lakes (Experimental)

Welcome to the repository for the AI Assistant for Data Lakes, an experimental project aimed at exploring how AI can transform business interactions with data. This initial experiment leverages OpenAI's API and is inspired by a previous GitHub project, serving as a foundational step toward future developments.

### Overview

This project represents the first step in developing a tool designed to assist with data management and analysis within a company. While the current iteration is experimental and not a fully functional product, it demonstrates the potential for automating data retrieval and analysis across various data sources—both structured and unstructured.

### Features (Experimental)

- **Data Retrieval and Analysis**: Experimentally integrates with SQL databases, CSV files, PDFs, and more, utilizing OpenAI's API to simulate answering complex queries.
- **Role-Based Access Control**: Conceptually explores how Retrieval Augmented Generation (RAG) could be used to tailor responses based on user credentials, ensuring secure data access.
- **Modular Architecture**: Designed to be easily extended and integrated into existing systems in future iterations.

### Future Experiments

Future development will focus on expanding this experiment into a fully functional AI assistant for business operations. Key areas of exploration include:

- **Self-Hosting with Meta's LLaMA Models**: Investigating the feasibility of using Meta’s LLaMA models to create a cost-effective, self-hosted solution, reducing reliance on external APIs.
- **Enhanced Role-Based Access**: Further developing RAG capabilities to ensure secure, credential-based access to various document types and data sources. Examples include employee contracts, SQL databases, CSV files, PDFs of internal documentation, expense reports, and other company files.
- **Business Operations Integration**: Expanding the assistant's capabilities to support a wide range of business operations, including decision-making processes, document management, and data retrieval across the company.

### Repository Structure

- `/data` - Contains datasets and related files.
- `/scripts` - Utility scripts for environment setup and data processing.
- `/src` - Source code for the experimental features, including Python scripts and modules.
- `.gitignore` - Specifies files to be ignored by version control.
- `README.md` - This file, providing an overview of the experiment and setup instructions.
- `requirements.txt` - Python dependencies required for the project.
- `task-definition.json` - AWS ECS task definition file for container configuration.


