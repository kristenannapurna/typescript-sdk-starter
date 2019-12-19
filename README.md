# Typescript SDK Starter

SDK starter based on [typescript-library-starter](https://github.com/alexjoverm/typescript-library-starter)

### NPM scripts

- `npm t`: Run test suite
- `npm start`: Run `npm run build` in watch mode
- `npm run test:watch`: Run test suite in [interactive watch mode](http://facebook.github.io/jest/docs/cli.html#watch)
- `npm run test:prod`: Run linting and generate coverage
- `npm run build`: Generate bundles and typings, create docs
- `npm run lint`: Lints code
- `npm run commit`: Commit using conventional commit style ([husky](https://github.com/typicode/husky) will tell you to use it if you haven't :wink:)

### Staging site for testing

Right now this repository is set up for automatic deployment to Netlify when master updates. A preview URL is generated for each pull request as well so that developers can test their code in a production environment too.

Staging Site: https://mystifying-goldberg-a14ff1.netlify.com/
