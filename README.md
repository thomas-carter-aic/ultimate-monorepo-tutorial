# 🌐 Ultimate Monorepo Tutorial

This repository is a **comprehensive tutorial** showing how [Ultimate Monorepo Project](https://github.com/thomas-carter-aic/ultimate-monorepo) was created using **Python**, **Go**, **Rust**, **Java**, and **TypeScript/Node.js**.

---

## 🛠 Prerequisites
Before starting, install or prepare:
- **Python** ≥ 3.10 ([Download](https://www.python.org/downloads/))
- **Go** ≥ 1.22 ([Download](https://go.dev/dl/))
- **Rust** ≥ 1.75 ([Install](https://www.rust-lang.org/tools/install))
- **Java** (JDK) ≥ 21 ([Download](https://adoptium.net/))
- **Node.js** ≥ 20 ([Download](https://nodejs.org/))
- Package managers: `pip`, `go mod`, `cargo`, `maven` or `gradle`, `npm`/`yarn`.
- Basic understanding of containers (Docker) and build tools.

---

## 📂 Tutorial Contents
| Step | Guide                                           | Description                              |
|------|-------------------------------------------------|------------------------------------------|
| 0    | [00-prerequisites.md](00-prerequisites.md)      | Install required tools and languages     |
| 1    | [01-environment-setup.md](01-environment-setup.md) | Set up a multi-language dev environment |
| 2    | [02-project-structure.md](02-project-structure.md) | Organize code for different languages   |
| 3    | [03-core-implementations/](03-core-implementations/) | Build components in Python, Go, Rust, Java, and TS |
| 4    | [04-integration.md](04-integration.md)          | Integrate polyglot components together   |
| 5    | [05-testing.md](05-testing.md)                  | Multi-language testing strategies       |
| 6    | [06-deployment.md](06-deployment.md)            | CI/CD and deployment tips               |

---

## 🔗 Related Repositories
- **Main Project:** [Ultimate Monorepo Project](https://github.com/thomas-carter-aic/ultimate-monorepo)  
- **Demo (Optional):** [Live Demo](https://example.com)

---

## 🖼 Screenshots & Diagrams
Include architecture diagrams and screenshots from the `/assets/` folder:  
![Architecture](assets/diagrams/architecture.png)

---

## 🧰 Tech Stack Highlights
- **Python**: Data processing or scripting  
- **Go**: High-performance microservices  
- **Rust**: Safety-critical components  
- **Java**: Enterprise backend services  
- **TypeScript/Node.js**: Frontend APIs or serverless functions  

---

# Documentation Website (this)

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

## Installation

```bash
yarn
```

## Local Development

```bash
yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```bash
yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

Using SSH:

```bash
USE_SSH=true yarn deploy
```

Not using SSH:

```bash
GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

---

## Mkdocs Commands

* `mkdocs serve` - Start the live-reloading docs server.
  - Visit http://127.0.0.1:8000 to preview.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.
* mkdocs gh-deploy
  - Deploy (to GitHub Pages)

---

## 🤝 Contributing
Contributions, fixes, and suggestions are welcome! Check [CONTRIBUTING.md](CONTRIBUTING.md) if available.

---

## 📜 License
Uses the same license as the main project (e.g., MIT or Apache 2.0).
