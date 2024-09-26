# SHIVAM ANAND DEV 03X

# Nx + Next.js + ShadCN Project

This project uses Nx, Next.js, ShadCN, and Tailwind CSS for a production-level application.

## Prerequisites

Before setting up the project, ensure that you have the following installed on your system:

- **Node.js** (version 16.x or higher)
- **npm** or **Yarn**
- **Nx CLI** (for managing the workspace)
- **Git**

## Project Structure

This repository contains the following structure:

## Getting Started

Follow these steps to set up the project locally:

### 1. Clone the repository

```bash
git clone <repository-url>
cd <repository-directory>
npm install -g nx
npm install
# or
yarn install
nx serve client
nx build client
nx lint client
nx test client

# ADD ADITIONAL APP
nx generate @nrwl/next:app new-app
nx generate @nrwl/workspace:lib shared-lib
```
