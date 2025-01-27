# Technical Roadmap

## Immediate 
- ~~Check on EOS on SQL 2019~~
- Containerise Galileo
- Containerise CM
- Validate/improve galileo multi-instance DB sharing, including implement federated caching

## Backend BAU
- Upgrade Galileo to JDK21
- Upgrade CM to JDK21
- Upgrade Galileo to Spring Boot 3.x.x current
- Upgrade CM to Spring Boot 3.x.x. current
- Upgrade dependency tree on Galileo
- Upgrade dependency tree on CM

## UI
- Update UI npm audit dependencies
- Upgrade all UI to Angular 18
- Complete UI builds extraction

## Improvements
- Migration of TR from C++ to .Net
- Re-baseline liquibase scripts for schema
  - Clean up starting data
- Explore migration to Postgres from Oracle
- Explore breakdown to multiple components for performance enhancement
- Parallelise load of drools, currently it's a simple for loop
- Explore further API improvements
- Test automation limited run part of PR code review pre-flight. Run smoke test suite, and improve execution speed.

## Miscellaneous
- [DISCUSS] move CONTENT_RESOURCE to filesystem
- Retire old Jenkins
- Restore or restrict SonarQube functionality
- Restore code coverage metric somehow
- One-click full builds
- Deploy Migration Tool as part of normal Galileo deployments
