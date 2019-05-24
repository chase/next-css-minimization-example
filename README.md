This repo is to demonstrate that `@zeit/next-css@0.2.1-canary.4` minimizes CSS as expected in a production build.

* Install with `npm install`
* Build the next project with `npm run build` (just runs `next build`)
* Note that the compiled CSS is minimized with `cat .next/static/chunks/styles.*.css`
