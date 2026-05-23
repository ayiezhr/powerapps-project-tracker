# Project Portfolio Management Model-Driven Power App

A professional Model-Driven Power App built on Microsoft Dataverse to manage corporate project pipelines, track team resource allocation, monitor task dependencies, and mitigate active operational risks.

## Key Features
- **Relational Dataverse Architecture:** Seamless Lookups mapping Tasks and Risks directly to Projects and Team Members.

## Repository Structure
- `/solution-packages`: Contains the unmanaged solution file ready to import directly into any Power Platform environment.
- `/demo-data`: Relational Excel mock data maps (numbered in suggested Dataverse import order).

## Dataverse Table Schema
1. **Project** (`Project Name`, `Description`, `Start Date`, `End Date`, `Progress %`, `Budget`)
2. **Team Member** (`Full Name`, `Role`, `Email`, `Phone Number`)
3. **Risk** (`Description`, `Project [Lookup]`, `Severity`, `Mitigation Plan`, `Timeline`)
4. **Task** (`Task Name`, `Description`, `Project [Lookup]`, `Due Date`, `Assign To [Lookup]`)
