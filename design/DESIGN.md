# Overview
Project Objectives:
1) Create a webpage using Angular/React libraries.
2) Create backend to handle requests and logic in Java using RESTful API.
3) Add DB Extension for ORM in backend
4) Create Container Image from project folder
5) Compile all test cases into more robust test suite

Additional Work:
1) Build Container to Serve Angular Pages, with note on SSR and SSG/Prerendering
    1) 'angular-front' app is currently init with 'zoneless' Angular and SSR, SSG/Prerendering
2) Create Dev Environment Container
3) Create localized desktop version of application
4) Implement CI/CD processes

# Project Phases
## Initialization
Setup basic Frontend and Backend libraries in Development Environment / Devcontainer
- Angular/React Frontend
- Java Springboot Backend

Setup project structure
- Folders separated by function
## Development
Setup branches for each feature
- Create Branch for Java Development
- Create Branch for Typescript Development
- (Optional) Optimize devcontainer packages

Setup test environment
- Create Unit Tests
- Create System Test
- Create Automated Testing Suite (Selenium? Others?)

## CI/CD
Setup Pipeline
- Git/Jenkins (Separate Container?)
- Optimize Docker Build
- Create 'UAT' and 'Staging' Branch (UAT should be accessible outsite? Reference more guides)

# Project Structure
Project structure should prioritize functionality before framework/language.

## Current Structure

/root
    /design
        /frontend
    /frontend
        /angular-front
        /python
    /backend
        /python
        /java

# Functional Design
- WIP
