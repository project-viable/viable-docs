# Project VIABLE website

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

You should only clone this repository if you are planning to make changes to the documentation/website.

### Installation

1. Install [Node.js](https://nodejs.org/en/download/package-manager)

2. Clone this repository
   ```git
   git clone git@github.com:project-viable/viable-docs.git
   ```
   
3. Navigate to the cloned directory
   ```bash
   cd viable-docs/
   ```
   
4. Install Docusaurus
   ```bash
   npm install
   ```

6. Start the site:
   ```bash
   npm run start
   ```

7. Point your browser to the localhost:3000

### Build

```bash
$ npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Local deployment

```bash
$ npm run serve
```

### GitHub pages deployment

The repository has been configured with a workflow. The page should build when branch `deploy` is pushed.

Note: You should check that Actions tab to ensure that the build was completed successfully. In particular, Docusaurus is configured to fail if a broken link is detected. This should not be overridden to help keep the website working correctly.

