

*Note that you will need to have [Node.js](https://nodejs.org) installed.*


## Get started

Dependencies

    axios: For making HTTP requests.
    uaparsers: For parsing user agent strings.

npm run dev


## Building and running in production mode

To create an optimised version of the app:

```bash
npm run build
```

## Single-page app mode

By default, sirv will only respond to requests that match files in `public`. This is to maximise compatibility with static fileservers, allowing you to deploy your app anywhere.

If you're building a single-page app (SPA) with multiple routes, sirv needs to be able to respond to requests for *any* path. You can make it so by editing the `"start"` command in package.json:

```js
"start": "sirv public --single"
```

## Using TypeScript

This template comes with a script to set up a TypeScript development environment, you can run it immediately after cloning the template with:

```bash
node scripts/setupTypeScript.js
```

Or remove the script via:

```bash
rm scripts/setupTypeScript.js
```
