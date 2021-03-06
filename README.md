# cryptoeconomiclabs.com
This is the source code for the [cryptoeconomicslab.com](https://www.cryptoeconomicslab.com) homepage

## About
Cryptoeconomics Lab is a team of distributed entrepreneurs, engineers, and blockchain experts.

## Features
- Dynamic routing with [express](https://github.com/expressjs/express) and [next-routes](https://github.com/fridays/next-routes).
- State management with [redux](https://github.com/reactjs/redux), [react-redux](https://github.com/reactjs/react-redux), and [next-redux-wrapper](https://github.com/kirill-konshin/next-redux-wrapper)
- Styling with SASS and render using [styled-jsx](https://github.com/zeit/styled-jsx)
- Unit testing with [jest](https://github.com/facebook/jest)
- Linting with [standard](https://github.com/standard/standard)
- [react-helmet](https://github.com/nfl/react-helmet), [Immutable.js
](https://github.com/facebook/immutable-js/), [dotenv](https://github.com/motdotla/dotenv), and more...

## Getting started
```
git clone https://github.com/cryptoeconomicslab/homepage.git homepage
cd homepage
yarn install
yarn start
```

Then open `http://localhost:3100/` to see your app.

## Structure overview
```
├── README.md
├── next.config.js
├── package.json
├── pages
│   ├── _document.js
│   ├── about.js
│   └── index.js
├── routes.js
├── server
│   └── index.js
├── src
│   ├── actions
│   │   └── repos.js
│   ├── components
│   │   └── SearchResults.js
│   ├── config.js
│   ├── containers
│   │   └── SearchRepoContainer.js
│   ├── libs
│   │   └── github.js
│   ├── reducers
│   │   ├── index.js
│   │   └── repos.js
│   ├── store
│   │   └── createStore.js
│   ├── styles
│   │   ├── SearchResults.scss
│   │   └── base.scss
│   └── test
│       ├── __mocks__
│       │   └── styleMock.js
│       ├── components
│       │   └── SearchResults.test.js
│       └── jest.setup.js
└── yarn.lock
```
