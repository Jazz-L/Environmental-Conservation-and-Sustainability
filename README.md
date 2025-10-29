metadata:
  title: "🌍 Environmental Conservation and Sustainability Dashboard"
  description: >
    Azure Synapse, SQL, Power BI, and PowerApps integration project showcasing 
    an end-to-end sustainability analytics solution aligned with Azure Data Engineer 
    certification concepts.
  author: "Jazz L."
  role: "Data Engineer | Azure | Power Platform | SQL | Power BI"
  email: "example@email.com"  # optional placeholder
  repo_url: "https://github.com/Jazz-L/Environmental-Conservation-and-Sustainability"
  created: "2025-10-28"
  version: "1.0.0"
  license: "MIT"  # or "Restricted - No external modifications"
  visibility: "public"
  tags:
    - azure-synapse
    - azure-data-engineer
    - power-bi
    - sql
    - powerapps
    - azure-devops
    - sustainability
    - data-engineering
    - portfolio-project

sections:

  - name: "Introduction"
    content: >
      This project demonstrates an end-to-end Azure data engineering workflow 
      focused on sustainability analytics. It integrates Azure Synapse Pipelines, 
      SQL Server, Power BI, and PowerApps, all managed through Azure DevOps for 
      CI/CD and task management. Each component aligns with key objectives from 
      the Microsoft Certified: Azure Data Engineer Associate exam — serving as both 
      a hands-on learning exercise and a real-world demonstration of data architecture, 
      transformation, and reporting in the Microsoft ecosystem.

  - name: "Project Structure"
    code_block: |
      Environmental-Conservation-and-Sustainability/
      │
      ├── 📁 sql/                     # SQL scripts for schema, tables, views, and stored procedures
      ├── 📁 synapse-pipelines/       # Azure Synapse pipeline JSON definitions
      ├── 📁 powerbi/                 # Power BI .pbix report files
      ├── 📁 powerapps/               # PowerApps export packages
      ├── 📁 automate/                # Optional Power Automate flows (if applicable)
      ├── 📁 diagrams/                # Architecture and data flow diagrams
      ├── 📄 README.md                # Project overview and setup guide
      └── 📄 LICENSE (optional)       # License information (if applied)

  - name: "Getting Started"
    steps:
      - step: "Clone the Repository"
        code_block: |
          git clone https://github.com/Jazz-L/Environmental-Conservation-and-Sustainability.git
          cd Environmental-Conservation-and-Sustainability

      - step: "Set Up Your Environment"
        tools:
          - Azure DevOps – for CI/CD pipelines, boards, and artifacts
          - Azure Synapse Analytics – for ETL workflows
          - SQL Server / Azure SQL DB – for structured data storage
          - Power BI Desktop – for building and testing dashboards
          - PowerApps – for creating interactive apps
          - SQL Server Management Studio (SSMS)
          - Azure Data Studio

      - step: "Database Setup"
        description: >
          Run SQL scripts in /sql to create all necessary objects — schema, tables, views, 
          and stored procedures. Alternatively, restore the provided database backup if available.

      - step: "Configure Synapse Pipelines"
        description: >
          Import pipeline definitions from /synapse-pipelines into your Azure Synapse workspace. 
          Update linked services, datasets, and credentials as needed.

      - step: "Power BI Reports"
        description: >
          Open .pbix files in Power BI Desktop, configure SQL connections, and publish to Power BI Service.

      - step: "PowerApps Setup"
        description: >
          Import the PowerApps package from /powerapps. Connect it to your SQL data source and 
          publish it to your PowerApps environment.

  - name: "Software Dependencies"
    table:
      - Tool: "SQL Server"
        Purpose: "Database storage, transformations, and queries"
      - Tool: "Azure Synapse Analytics"
        Purpose: "Data ingestion, orchestration, and transformations"
      - Tool: "Power BI Desktop"
        Purpose: "Visualization and reporting"
      - Tool: "PowerApps"
        Purpose: "Front-end app interface"
      - Tool: "Azure DevOps"
        Purpose: "CI/CD automation, version control, and task tracking"

  - name: "Build & Test"
    subsections:
      - title: "Build Process"
        steps:
          - "Execute SQL scripts to build database structures."
          - "Import Synapse pipeline definitions and validate connections."
          - "Refresh Power BI reports to confirm proper data integration."
          - "Load PowerApps and confirm functionality with SQL data."
      - title: "Test Coverage"
        items:
          - "Unit Tests: Validate stored procedures and SQL transformations."
          - "Integration Tests: Confirm full data flow (Synapse → SQL → Power BI → PowerApps)."
          - "User Acceptance Tests (UAT): Validate business logic with sample data."

  - name: "Documentation & References"
    links:
      - "SQL Server Documentation: https://learn.microsoft.com/sql/sql-server/"
      - "Azure Synapse Analytics: https://learn.microsoft.com/azure/synapse-analytics/"
      - "Power BI Documentation: https://learn.microsoft.com/power-bi/"
      - "PowerApps Documentation: https://learn.microsoft.com/powerapps/"
      - "Azure DevOps Documentation: https://learn.microsoft.com/azure/devops/"

  - name: "Project Status"
    content: >
      This is an independent portfolio project created for learning and demonstration purposes. 
      External edits, pull requests, and feature contributions are not accepted.  
      You’re welcome to fork or reference this repository for educational use — 
      please credit the original author.

  - name: "Author"
    details:
      name: "Jazz L."
      title: "Data Engineer | Azure | Power Platform | SQL | Power BI"
      links:
        - "LinkedIn: #"
        - "GitHub: https://github.com/Jazz-L"
