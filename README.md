# Next.js + NestJS

This repository is focused on studying the integration of **Next.js** and **NestJS** to create a blog. The objective is to showcase how these technologies can be effectively combined to build scalable, full-stack applications, emphasizing type safety and enhancing developer productivity.

## Getting Started

### Installation
We use `pnpm` as the package manager for this project. To install the dependencies for the entire monorepo, simply run:

```bash
pnpm install
```


### Running the Application
To start both the front-end (Next.js) and back-end (NestJS) servers in development mode, use the following command:
```bash
pnpm run dev
```
This will run both **front-end** and **back-end** concurrently.

### Installing Packages
To add dependencies to either the client or server separately, use the `--filter` flag with `pnpm`. For example:

**Adding a package to the client:**
```bash
pnpm add <package-name> --filter=client
```
**Adding a package to the server:**
```bash
pnpm add <package-name> --filter=server
```

### Directory Structure
Here’s an overview of the project structure:
```bash
├── apps/
│   ├── client/   # Next.js front-end application
│   ├── server/   # NestJS back-end application
├── package.json   # Root package configuration
└── pnpm-workspace.yaml # pnpm workspace configuration
```