# Dynamic Hit Counter exercise

Once again, we're working on our hit counter!

This time, everything works swell when we run in development, but things don't quite work when we try to build for production; The number of hits appears fixed in place, and doesn't increase when we refresh the page.

Your mission is to fix this bug!

## Helpful NPM commands

First, install the dependencies:

```bash
$ npm install
```

You can run a local development server with:

```bash
$ npm run dev
```

In this exercise, though, you'll want to run the application in _production._ You can do that by first generating a production build, and then starting a production server:

```bash
$ npm run build

# ...then, once the build is completed:
$ npm run start
```

I also created a helper script, `start:local`, which you can run if you get an error message about port conflicts:

```bash
$ npm run start:local
```

It does the exact same thing, but starts the server on port 4000.
