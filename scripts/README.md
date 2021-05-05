<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

**Table of Contents**

- [Scripts](#scripts)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Scripts

This directory contains scripts for working with the GRANDstack Starter monorepo and should be run as npm scripts from the root directory. For example

```
npm run start
```

- `start-dev.js` - starts the GraphQL API and web-react servers
- `build.js` - builds the api and web-react projects
- `inferSchema.js` - connect to Neo4j and generate inferred GraphQL type definitions, written to `./api/src/schema.graphql`
- `seed.js` - seeds the database locally from the api directory
