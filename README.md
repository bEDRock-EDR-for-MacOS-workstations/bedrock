# bEDRock

Endpoint Detection and Response for MacOS workstations

## Project structure

* api: OpenAPI/Swagger specs, JSON schema files, protocol definition files.
* cmd: main applications for the Project.
* configs: Configuration file templates or default configs.
* docs: Design and user documents.
* init: System init (systemd, upstart, sysv) and process manager/supervisor (runit, supervisord) configs.
* scripts: assets to perform various build, install, analysis, etc operations.
* test: integration, load and further cross modules tests

reference: https://github.com/golang-standards/project-layout

## Development environment

### Installing
...

## Contributing
We are using truncate to format the code, so please use it before sending a pull request.

The branch pattern should be:

| Branch name            | Purpose                        |
|------------------------|--------------------------------|
| `feat/<ticket-id>`     | Feature implementations        |
| `fix/<ticket-id>`      | Fixing bugs                    |
| `docs/<ticket-id>`     | Adding documentation           |
| `style/<ticket-id>`    | Just code style organizations  |
| `chore/<ticket-id>`    | Cleaning tasks or general ones |
| `refactor/<ticket-id>` | Code structure being changed   |


They should always be created from `main` branch, and then create a PR to development branches as needed.
