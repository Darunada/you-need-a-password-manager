# YouNeedAPasswordManager.com

![Check](https://github.com/Darunada/you-need-a-password-manager/workflows/Check/badge.svg)

Description
--------------------------------------
Just for fun.  Do you need a password manager?  YES! already.

I am making this project to learn and play around with Vue.


Installation
--------------------------------------
This site is built in Vue.  Is this your first time?  It is mine @_@

- You have node installed, preferably via `nvm`
- Build and install the program with 

```
$ npm ci
  ... builds in a few minutes ...
$ npm run serve
```

Usage
--------------------------------------

This application has tests.  You can run tests with the following commands:

```
npm run test:unit
npm run test:e2e
npm run lint
```

Compiles a production build with:

```
npm run build
```

Roadmap
--------------------------------------
My plan is to have an entry for a user's email to check against the HaveIBeenPwned api.  No matter the response, it will say yes, and provide an alert if applicable.

I will host the API request in a Cloudflare Worker if I can swing it.
