# phoenix-skeleton

A starter to get my Phoenix projects up and running. Mainly used for easy-bake `podman`/`postgres` integration.

## Instructions

1. Create your project: `mix phx.new your_project_name`
2. Add project info to the `.env` file.
3. Use the `start` script to start the Postgres container and the Phoenix server.
  - During the first run, pass `--init` as the first argument to set up the database.
    - e.g. `start --init`
