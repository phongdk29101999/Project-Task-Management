# PUROJEKUTO
## Requirements
- Docker CE
- NodeJS & NPM
## Initialize CLI file
```
cp project-cli.example project-cli && sudo chmod +x project-cli
```
## Initialize necessary files
```
./project-cli init:file
```
## Add static local ip for macos
> Everytime macos restart, run follow command again
```
./project-cli init:ip
```
## Build and run
```
docker-compose build && docker-compose up -d
```
## Load env file
```
./project-cli load:env
```
## Migration && Seed
```
docker-compose exec app php artisan migrate && docker-compose exec app php artisan db:seed
```
## Load host
```
./project-cli load:host
```
## Load package
```
./project-cli load:package
```
## Access to project [http://purojekuro.test.com](http://purojekuto.test.com)
