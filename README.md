This is an example repo for the next.js issue https://github.com/vercel/next.js/issues/32115

To trigger the issue:

```shell
yarn install
yarn build
```

Currently, the `swcFileReading` is set to false, which triggers the react query issue.
To trigger the original `Error: Failed to read source code from` error, remove the `experimental` flag from `next.config.js`.