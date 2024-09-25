# GraphQL Server

### A GraphQL server built in Go using gqlgen, designed to handle GraphQL queries efficiently with a database integration.


<h5>Features</h5>
<ul>
  <li> GraphQL: Handles queries and mutations using gqlgen.  </li>
  <li> Database: Uses SQLite for persistent data storage. </li>
  <li> Go Modules: Managed with Go modules for easy dependency management. </li>
</ul>

<h5>Getting Started</h5>
<h6>Prerequisites</h6>
<ul>
  <li> Go 1.18+ </li>
  <li> SQLite </li>
</ul>

<h6>Setup</h6>

1. Clone the repository

```

git clone https://github.com/arthurssn/graphql
cd graphql

```

2. Install dependencies

```

go mod tidy

```


3. Install dependencies

```

go run cmd/server/server.go

```

<h5>Project Structure</h5>

<ul>
  <li> cmd/server: Entry point for running the server.</li>
  <li> internal/database: Database setup and connection.</li>
  <li> graph: GraphQL schema and resolver implementations.</li>
</ul>
