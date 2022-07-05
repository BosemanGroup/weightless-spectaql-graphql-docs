# SpectaQL

Framework documentation: https://github.com/anvilco/spectaql

#### Setup
```
npm install -g spectaql
```
In root of project:
```
npm install
```

#### Customise theme styles
- Theme directory: src/themes
- Each folder refers to a different theme, themes build on top of the default theme. To change which theme is active,
update the themeDir property in examples/config.yaml.
- Find a style you want to override in the default theme and copy the structure of that style in the theme directory
that you are working on

#### Update response examples 
- Modify file: examples/data/metadata.json

#### Update operations & types
- Modify graphql schema file: examples/data/schema.gql

#### Update Introduction
- Open file: examples/config.yaml
- Modify relevant property under info

#### Test locally
```
npm run develop ./examples/config.yml
```
- View docs in browser with url: http://localhost:4400/

#### Deploy
- Generate docs:
```
npx spectaql examples/config.yml
```
- Copy public/ and replace docs/ 
- Commit and push changes to main Git branch
- Wait for GitHub actions to build docs
- View docs at https://bosemangroup.github.io/weightless-spectaql-graphql-docs/