# Vugu Tutorial

- This GitHub client is created with WebAssembly framework called Vugu for tutorial.

## for develop

```sh
go run server.go -dev
```

## for production

```sh
go run dist.go # generate static files
cd dist
serve
```

## for deploy

```sh
npm install
npm run deploy
git pull
git checkout gh-pages
git push heroku master
```
