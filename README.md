# Agile Data Platform

Architecture and documentation for a truly agile data platform

## Introduction

This repository is intended to provide examples and explanations of how to architect a modern cloud data platform which is driven by DevOps processes and allows enterprise scale in terms of both capability and work throughput. It is designed to remove unnecessary blockers and issues which arise with more traditional approaches by following the example of application development. Concepts such as "Cattle vs Pets" and loose coupling will be central to this architecture, alongside a modular approach with strong, contract based interactions between components. The documents here describe the platform as a whole and should not be confused with data engineering or data modelling documentation both of which still have their place inside of data products alongside aspects such as data quality and compliance.

The agile data platform can be broken down into several topics, each of which can be considered independently if retrofitting into an existing practice, or together if starting from scratch. 

### Structured Testing

This is an often misunderstood subject within the data practice since it does not focus on testing the data but rather the implementation. Structured testing allows you to perform unit testing and integration testing against your data platform and pipeline components to ensure quality and consistency.

[Structured Testing](docs/testing)

### DataOps

DataOps are a set of processes and methods for managing a project and product development. While this may include some automation it is not simply scripted deployment. DataOps is the bringing together of the skills and people needed to successfully build a data product. These include data modelling, data engineering, testing, infrastructure, security, networking, disaster recovery and backup, reporting, monitoring and of course support. Each of these skills and more must be represented within the team to allow frictionless progress to be made, removing the need for change controls between departments and placing the responsibility directly with the project team itself. The processes here allow for quality checks and tests to be made during each development cycle, giving confidence that the next product release will do everything expected, with any issues and feedback being dealt with by the team itself.

[DataOps](docs/dataOps.md)

### Agile Platform Architecture

Processes can make delivery more agile, but beyond a certain point team size becomes an issue and complexity starts to overtake agility and slow progress. To prevent this, a different architecture is needed which can break the problem down into smaller tasks and projects and make them more manageable. Traditionally data platforms have been architected as end to end processes from source to destination with long interlinked ETL or ELT pipelines each interdependent to the point that one failure will break the whole system. With an agile data approach our aim is to follow the loosely coupled, highly focused "micro-service" approach from application development.

## Docs

[Architectural Principles](docs/architecturalPrinciples.md)

[Glossary of terms](docs/glossary.md)
