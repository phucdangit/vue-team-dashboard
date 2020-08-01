# Vue Teamwork Dashboard

A internal dash board build with Vue JS, Laravel for summarize team status at the moment. The data will be refreshed in realtime, some can be configured to be reloaded with a fix timer.

<img width="500" alt="portfolio_view" src="https://github.com/phucdangit/vue-team-dashboard/blob/master/source/docs/images/screenshot20170127.jpg?raw=true">
 
## Tech Stacks

- [Vue CLI 3](https://github.com/vuejs/vue-cli)
- [Vue](http://vuejs.org/)
- [Sass](http://sass-lang.com/)
- [Laravel](https://laravel.com/)

## Prerequisites:

- Node/NPM
- Vue-cli 3.x
- Docker/Docker-compose

## Project setup
```
cd docker
docker-compose up -d
docker-compose exec dashboard_web composer install
docker-compose exec dashboard_web yarn install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```