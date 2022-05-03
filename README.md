## SCC

Welcome to my submission for the SCC 🚀

### Getting Started

1. Clone this repository: `git clone https://github.com/nrademacher/scc`
1. In the root directory, pull the `frontend` and `backend` submodules: `git submodule update --init`
1. Set up `backend` env data: `cp backend/.env.example backend/.env`
1. Run `docker-compose up`

Now the NextJS frontend should be available at `http://localhost:3000` :)

The GraphQL server is at `http://localhost:4000/graphql` and, additionally, the database can be inspected at `http://localhost:5000`
