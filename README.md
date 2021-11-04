# Vue .env POC

*Note: All .env variables must start with `VUE_APP_` in order for Vue to ingest them at build time*
## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build-dev
yarn build-staging
yarn build-prod
```

These will build each of the different dev branches, copying the environment file for each level into `.env` before building:

```
.env-dev
.env-staging
.env-production
```