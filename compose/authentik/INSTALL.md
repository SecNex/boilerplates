# Authentik

## Clone the repository

```shell
git clone https://git.serverify.de/SecNex/boilerplates.git
cd boilerplates/authentik
```

## Create the .env file

```shell
cp .env.example stack.env
```

## Create new passwords and secrets

```shell
# Secrets
openssl rand -base64 32
# Passwords
openssl rand -hex 32
```

## Edit the .env file

```shell
nano stack.env
```

## Start the stack

```shell
docker-compose up -d