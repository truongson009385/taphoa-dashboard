## Overview

TailAdmin provides essential UI components and layouts for building feature-rich, data-driven admin dashboards and control panels. It's built on:

- Next.js 15
- React 19
- TypeScript
- Tailwind CSS

## Installation

### Prerequisites
To get started with TailAdmin, ensure you have the following prerequisites installed and set up:

- Node.js 18.x or later (recommended to use Node.js 20.x or later)

### Cloning the Repository
Clone the repository using the following command:

```bash
git clone https://github.com/TailAdmin/free-nextjs-admin-dashboard.git
```

> Windows Users: place the repository near the root of your drive if you face issues while cloning.

1. Install dependencies:
    ```bash
    npm install --legacy-peer-deps
    # or
    yarn install
    ```
    > Some included packages causes peer-deps issue with React 19 while installing.
    >
    > With npm the `--legacy-peer-deps` flag is a workaround for that at the moment.

2. Start the development server:
    ```bash
    npm run dev
    # or
    yarn dev
    ```