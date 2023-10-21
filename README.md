# Blockchain_l5_etherjs_simple

Running on ubuntu 22.04 wsl:

Install

- install npm on windows
- install nodejs on windows
- install nvm on wsl : curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash
- install the same version on nodejs like on windows : nvm install 18.18.2
- npm install solc
  corepack enable
  yarn --version

  On project:
  installing solc with yarn : yarn add solc@0.8.8 (same as solidity)
  yarn add ethers
  yarn add fs-extra
  yarn add dotenv
  yarn add prettier prettier-plugin-solidity

  Typescript:
  yarn add typescript
  yarn add ts-node
  yarn add @types/fs-extra

  Compiling :
  yarn compile (command added in package.json)

  Running:
  node deploy.js
  or
  yarn ts-node deploy.ts
