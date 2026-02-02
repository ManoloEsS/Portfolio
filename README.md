# Personal Projects

## Burrow

[Burrow](https://github.com/ManoloEsS/burrow) is a terminal-based HTTP client and Go server manager. Its HTTP client functionalities are similar to [postman](https://www.postman.com/) and [atac](https://github.com/Julien-cpsn/ATAC).
The server manager is a service that can run and stop a Go server program and monitor their health. 

The motivation behind this project was to provide students learning how to make and use REST APIs with a tool to start simple Go servers and test them
from the same environment.

### Architecture

Burrow has a layered architecture with:

- Presentation layer: TUI built with [tview](https://github.com/rivo/tview).
- Service layer: HTTP client service and Server service.
- Database layer: SQLite embedded database with SQLC generated type-safe code.

## Cli Password Manager


# Boot.dev Learning Projects

This section serves as a hub for the projects I built while learning backend development through [Boot.dev](https://boot.dev).  
These projects have increased in complexity and scope as I have acquired new skills and knowledge; they are listed in the reverse order in which I completed them.


Each project has its own repository with:
- Source code
- Documentation

These are educational exercises that show my progression as I learned new skills and concepts.

## Projects

| Project Name | Link | Description | Language | Key Learnings |
|---------|------|-------------|---------|---------------|
| Gator CLI  | [Repo](https://github.com/ManoloEsS/gator_cli) | Cli RSS feed aggregator | Go | PostgreSQL databases and HTTP servers |
| Pokedex CLI | [Repo](https://github.com/ManoloEsS/pokedex) | Cli REPL that retrieves pokemon data from PokeAPI.co  | Go | JSON parsing, HTTP clients and requests, caching |
| Static Website Generator | [Repo](https://github.com/ManoloEsS/my_static_website) | Static site generator that reads a markdown file and recursively converts it into html | Python | HTML, CSS, Markdown, static sites, recursion, testing|
| AI Agent | [Repo](https://github.com/ManoloEsS/ai_agent) | AI Agent that can read and modify code files | Python | multidirectory projects, AI tools, functional programming, unit tests |
| Asteroids | [Repo](https://github.com/ManoloEsS/asteroids) | Asteroids game built with pygame | Python | OOP, multifile projects, uv package and project manager |
