# Confab ( "Modular monolith" )
Backend application for managing conferences, speakers, tickets etc. modules, every module is "talking" to other ones by events. project made by following a devmentors "Modular Monolith" course.

## Arhitecture
Projects is consisted of modules which some of them are based on Clean Architecture and CQRS ( Attendances, Agendas module ) and rest of them are based Modular Monolith.

- Confab/Shared/Abstractions ( project with abstraction / interfaces for modules )
- Confab/Shared/Infrastructure ( project with shared code which is used by modules and depenendencies registrations)
- Confab/Modules/Tests/Integration / Unit ( projects with unit / integration tests for controller and modules handlers )

Additionaly project have  main .rest files with examples of basic requests and docker-compose.yaml file for setting up a docker container.
## Main Tech Stack
- NET 5
- Postgres
- Docker




 
