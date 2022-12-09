# phoenix-starter

A starter to get my Phoenix projects up and running. Mainly used for easy-bake `podman`/`postgres` integration.

## Instructions

1. Create your project: `mix phx.new your_project_name`
2. Update the value of `POSTGRES_DB` in `.env` so that it contains the name of your project.
3. Start the `postgres` container: `podman-compose up`
4. Run `mix ecto.create`
5. Run `mix phx.server`
