
<!-- # Badges -->

[![Github issues](https://img.shields.io/github/issues/2f0833e717/manual)](https://github.com/2f0833e717/manual/issues)
[![Github forks](https://img.shields.io/github/forks/2f0833e717/manual)](https://github.com/2f0833e717/manual/network/members)
[![Github stars](https://img.shields.io/github/stars/2f0833e717/manual)](https://github.com/2f0833e717/manual/stargazers)
[![Github top language](https://img.shields.io/github/languages/top/2f0833e717/manual)](https://github.com/2f0833e717/manual/)
[![Github license](https://img.shields.io/github/license/2f0833e717/manual)](https://github.com/2f0833e717/manual/)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [how to start guide](#how-to-start-guide)
  - [fix initial start guide](#fix-initial-start-guide)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# how to start guide
> <https://github.com/grand-stack/grand-stack-starter>

```bash
npm run seedDb
```
or
```bash
docker-compose up -d
```
or
```bash
docker-compose run api npm run seedDb
```

## fix initial start guide
```bash
# vi package.json
  "lint-staged": {
    "*.js": [
      "prettier --write"
      "eslint --fix" # <= delete row
    ]
  }
```
