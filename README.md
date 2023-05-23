# re:side

The gateway for the re:side project

re:side contains the core data structures that will be used in re:stocky and re:sippy.
The data is stored in dgraph containers.

To use you need to:
1. yarn add @apollo-server graphql
2. docker compose up -d
3. Post /subgraphs/reside.graphql to dgraph (the generated schema is already at subrgraphs/reside.graphql)
4. yarn start
5. Open appsmith in your browser and add the supergraph as the datasource

re:sippy and re:stocky are coming soon and will contain app level functions for stock and recipe management.
