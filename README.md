This is a Next.js project that reproduces [this error with Auth0-Lock](https://github.com/auth0/lock/issues/2051) that breaks building SSR components if Lock is imported.

You should not be able to build this project, you will instead get a build error that `window is not defined`.
