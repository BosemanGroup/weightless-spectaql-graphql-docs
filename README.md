# SpectaQL

Framework documentation: https://github.com/anvilco/spectaql

#### Update response examples 
- Open file: examples/data/metadata.json
- Find and replace text

#### Update schema
- Modify file: examples/data/schema.gql

#### Test locally
- npm install
- npm run develop ./examples/config.yml
- View docs in browser with url: http://localhost:4400/

#### Deploy
- Copy examples/output/ and replace docs/ 
- Push to main branch
- Wait for github action to build docs
- View docs at https://bosemangroup.github.io/weightless-spectaql-graphql-docs/