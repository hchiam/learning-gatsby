# Learning Gatsby.js

Just one of the things I'm learning: https://github.com/hchiam/learning

## Quick setup of an example Gatsby starter called [gatsby-starter-deck](https://www.gatsbyjs.org/starters/fabe/gatsby-starter-deck/)

```bash
npm install -g gatsby-cli
gatsby new gatsby-starter-deck https://github.com/fabe/gatsby-starter-deck
npm run build
npm run develop
```

http://localhost:8000

Edit a file and the page reloads in real time:
* For example, editing the markdown file `gatsby-starter-deck/src/slides/01-intro.md` triggers the [intro page](http://localhost:8000) to auto-update live.
* Try editing the React.js code in `gatsby-starter-deck/src/layouts/index.js` and notice changes in the [first slide](http://localhost:8000/1) when you edit the JSX ("HTML") inside the `render()` method.

## Tutorial

https://www.youtube.com/watch?v=b2H7fWhQcdE&list=PLLnpHn493BHHfoINKLELxDch3uJlSapxg&index=2&t=0s

```bash
npm install -g gatsby-cli
gatsby new my-gatsby-site
cd my-gatsby-site
gatsby develop
```

http://localhost:8000
