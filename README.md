&nbsp;
<img src="/assets/ebcont-base_digitalisnow-tuerkis.png" alt="ebcont logo" width="350px">

# GitHub Flow, Actions & Tools: Hands-On Workshop

This repository contains a sample application used for the Training "GitHub Flow, Actions & Tools".
It's purpose is to demonstrate the EBCONT GitHub experience.

- Organization has a Custom Property "code-rulesets" with values:
  - "branch-default", "branch-review", "branch-conventional-commits" and "tag-default"
- Branch & tag rulesets are activated on the repository through the chosen custom property value(s)
- Tools: 
  - Release Please&emsp;&emsp;[Release & Changelog automation](<https://github.com/googleapis/release-please>)
  - Dependabot&emsp;&emsp;&emsp;[Dependency management](<https://docs.github.com/en/code-security/getting-started/dependabot-quickstart-guide>)

## Contact persons

- Andreas Titz (andreas.titz@ebcont.com)
- Georg Brandstätter (georg.brandstaetter@ebcont.com)

## Prerequisites

- GitHub account to fork the repository
- Maven installed on your machine

## Sample App description

A simple Spring Boot application displaying an index and a greetings page:
- Index page with a link to the greetings page
  - Has an error in the header that will be fixed during the workshop 
- Greetings page displays "hello world" message
  - Has an additional argument that will be used to add a feature during the workshop 
- Maven POM file has an outdated dependency of "spring-boot-starter-logging"
  - Used to demonstrate how Dependabot works  

## GitHub workflows are located under .github/workflows/
- ci.yml | build, test & publish  
- ci-integration-tests.yml
- release-please.yml

## GitHub Tool configuration:
- .github/dependabot.yml
- .release-please-manifest.json
- release-please-config.json
- CODEOWNERS

## Getting started

- Fork the repository to your GitHub account
- Check out the project locally

- Run `mvn clean install` to build the project
- Run `mvn spring-boot:run` to start the app
- Navigate to localhost:8080 with a browser

## hidden stuff


Follow the tasks in the workshop :rocket:


