# Technical Roadmap

## Immediate 
- Check on EOS on SQL 2019
- Containerise Galileo
- Containerise CM

## Java
- Upgrade Galileo and CM to JDK21
- Upgrade Galileo to Spring Boot 3.x.x current
- Upgrade dependency tree on Galileo
- Upgrade CM to Spring Boot 3.x.x. current
- Upgrade dependency tree on CM

## UI
- Update UI npm audit dependencies
- Upgrade all UI to Angular 18
- Complete UI builds extraction

## Improvements
- Re-baseline liquibase scripts for schema
  - Clean up starting data
- Explore breakdown to multiple components for performance enhancement
- Parallelise load of drools, currently it's a simple for loop
- Explore further API improvements

## Miscellaneous
- [DISCUSS] move CONTENT_RESOURCE to filesystem
- Retire old Jenkins
- Restore or restrict SonarQube functionality
- Restore code coverage metric somehow
- One-click full builds
- Deploy Migration Tool as part of normal Galileo deployments
