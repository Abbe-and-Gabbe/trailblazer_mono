# Trailblazer mono repository

This repository contains submodules for the different parts of the Trailblazer project.

__DO NOT PUSH ANYTHING TO THIS PROJECT, ONLY TO THE SUBMODULES__

# How to clone?

Since this project uses submodules, use the following command to clone the repository:

```sh
git clone --recursive https://github.com/Abbe-and-Gabbe/trailblazer_mono
```

## Update submodules (Ask @albin02forsberg if needed)

```sh
git submodule update --init --recursive
```

# Docker

This project uses docker compose to dockerize all the smaller projects together.

- Frontend (next)
- Backend (nest)
- Database (postgres)
- DBMS (pgadmin)

# Trailblazer

For documentation about the different modules of Trailblazer, se the documentation for each project.

- [Frontend](https://github.com/Abbe-and-Gabbe/trailblazer/wiki)
- [Backend](https://github.com/Abbe-and-Gabbe/trailblazer_backend/wiki)
- [~Trailblazer Data Cruncer~]()