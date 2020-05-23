[![default](https://user-images.githubusercontent.com/7531596/81993396-d5142b00-9645-11ea-995f-98342b7d5c8f.png)](https://github.com/wlucha/angular-starter)  
# Angular 9 + Material + Transloco + Jest + Compodoc + Docker
Angular 9 Starter with Material, Transloco, Jest &amp; Compodoc  
by [@wlucha](https://github.com/wlucha)

[![Build](https://api.travis-ci.org/wlucha/angular-starter.svg?branch=master)](https://travis-ci.org/github/wlucha/angular-starter)
[![MIT](https://img.shields.io/packagist/l/doctrine/orm.svg?style=flat-square)]()
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=wlucha_angular-starter&metric=alert_status)](https://sonarcloud.io/dashboard?id=wlucha_angular-starter)
[![Docker Pulls](https://img.shields.io/docker/pulls/wlucha/angular-starter)](https://hub.docker.com/repository/docker/wlucha/angular-starter)
[![Docker Image Size (latest by date)](https://img.shields.io/docker/image-size/wlucha/angular-starter)](https://hub.docker.com/repository/docker/wlucha/angular-starter)
![David](https://img.shields.io/david/wlucha/angular-starter)

<!---
[![dependency Status](https://david-dm.org/wlucha/angular-starter.svg)](https://david-dm.org/wlucha/angular-starter#info=dependencies)
[![devDependency Status](https://david-dm.org/wlucha/angular-starter/dev-status.svg)](https://david-dm.org/wlucha/angular-starter#info=devDependencies)
-->
  
## Features    
✅ Angular 9+   
✅ Angular Material Theming  
✅ Jest Unit Testing  
✅ Internationalization with Transloco  
✅ Auto documentation with Compodoc  
✅ Analyse your project with webpack-bundle-analyzer  
✅ Docker Support

## Deploy
[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Demo
- [StackBlitz Demo](https://stackblitz.com/github/wlucha/angular-starter)

## Install / Development

```bash
git clone https://github.com/wlucha/angular-starter
cd angular-starter

# Install dependencies
npm install

# Start server
npm run start

# Open in browser: http://localhost:4200
```

## Docker Deployment
```bash
# Build Docker image
docker build . -t angular-starter  

# Run Docker Container
docker run -p 3000:80 angular-starter
```

## Docker Hub
https://hub.docker.com/r/wlucha/angular-starter

## Commands
- `npm run start`             - start the app
- `npm run test`              - run unit tests
- `npm run build`             - build the project
- `npm run build:prod`        - build the project in production mode
- `npm run build:prod:stats`  - build the project in product mode with stats
- `npm run analyse`           - analyse bundle with [webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer)
- `npm run compodoc`          - generate [compodoc](https://github.com/compodoc/compodoc) documentation
- `npm run changelog`         - generate changelog
