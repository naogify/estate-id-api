#  不動産 ID API

## development

```shell
$ git clone geolonia/estate-id-api
$ cd estate-id-api
$ cp .envrc.sample .envrc
$ vim .envrc # fill the values
$ yarn # or `npm install`
$ npm test
```

### update Snapshot test

```shell
$ npm test -- -u
```

## deploy

```shell
$ npm run deploy:dev
```

## Utilities

```shell
# put an api key
$ npx ts-node ./src/bin/put-api-key.ts api-key accesss-token
```