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

# Recommended workflow

As mentioned before, __DO NOT__ push anything without permission to the `trailblazer_mono` repo.

It is recommended that you open for example `frontend` and only work from that directory. By doing 
this, you treat it as a normal repository, and all the commits will be pushed to that repository.

# Trailblazer

For documentation about the different modules of Trailblazer, se the documentation for each project.

- [Frontend](https://github.com/Abbe-and-Gabbe/trailblazer/wiki)
- [Backend](https://github.com/Abbe-and-Gabbe/trailblazer_backend/wiki)
- [~Trailblazer Data Cruncer~]()