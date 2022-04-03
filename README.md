# Learn Adonis

[Documentation](https://docs.adonisjs.com/)

## Starting the development server

```bash
node ace serve --watch
```

## Compiling for production

```bash
node ace build --production
```

```bash
cd build
node server.js
```

## Configure: Database

```bash
yarn add @adonisjs/lucid
node ace configure @adonisjs/lucid
```

## Migration

```bash
node ace make:migration users
node ace migration:run
```

## Seed

```bash
node ace make:seeder User
node ace db:seed
```
