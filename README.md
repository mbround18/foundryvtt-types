# Foundry VTT Types

Compiled types from FoundryVTT, working on a way to automate it but this should get you started. Note, this may not be complete as its all the generated types in the client directory. I am also working on getting this automated for any new releases. 

## Installation

### NPM

```sh
npm install -D foundryvtt-types
```

### Yarn

```sh
yarn add -D foundryvtt-types
```

## Setup

After installation you have to add the following to your `tsconfig.json`

```json
{
  "types": ["./node_modules/foundryvtt-types"]
}
```
