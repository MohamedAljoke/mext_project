# Mext

This is a plataform for online courses for the mext scholarship

## Cloning

Add the `--recurse-submodules` flag when cloning this repo

### Init Submodules

If you did not clone with the flag `--recurse-submodules`, init the submodules with:

```sh
git submodule update --init --recursive
```

copy .env file

```
cp ./mext-admin/.env.example ./mext-admin/.env
cp ./mext-front/.env.example ./mext-front/.env
cp ./mext-plataform-api/.env.example ./mext-plataform-api/.env
cp ./mext-plataform-api/.env.example .env
```

run docker compose

```
docker-compose up -d
```
