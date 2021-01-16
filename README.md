# Simple Bank
Mini project to learn TDD in golang

## Dependencies

- Install golang-migrate
`brew install golang-migrate`

- Install sqlc
`brew install sqlc`

## Setup
Start docker engine and make sure you have a postgres12 docker image
execute
1. `make postgres`
2. `make createdb`
3. `make migrateup`

## Testing
`make test`
