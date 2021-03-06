[![Build Status](https://travis-ci.org/hdf1986/money-management.svg?branch=master)](https://travis-ci.org/hdf1986/money-management)

# Money Management
![Screenshot](https://github.com/hdf1986/money-management/raw/master/screenshot.png)


## Node version
It's suggested to run at least Node V10.16.3

## Installation
To install the packages you need to run

```bash
npm install
```

## Development
Running the following command it wil autoreload the express server and also run parcel with HMR enabled
```bash
npm run dev
```

## Testing and linting
There are no tests yet because the lack of time

To run the linter you can do:
```bash
npm run lint
```
and to use the autofix function of Eslint
```bash
npm run lint:fix
```

## Production mode
In order to run the app in production mode you should do:

```
NODE_ENV=production npm start
```
