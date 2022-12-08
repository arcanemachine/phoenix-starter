# phoenix-starter

A starter to get my Phoenix projects up and running. Mainly used for easy-bake `podman`/`postgres` integration.

## Instructions

1. If `direnv` is not installed on your system, install it now: `https://direnv.net/`
2. Create your project: `mix phx.new your_project_name`
3. Add project info to the `.env` file.
4. Run `direnv allow` so that your environment reflects the contents of the `.env` file.
5. Use the `start` script to start the Postgres container and the Phoenix server.
  - During the first run, pass `--init` as the first argument to set up the database.
    - e.g. `start --init`
6. To add the project to a Git repo, delete the `.git` folder in the root directory of the project, and create a new git repo with `git init`.
