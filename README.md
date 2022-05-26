```bash
yarn install
yarn tsc
```

Error:

```
index.ts:3:13 - error TS2339: Property 'get' does not exist on type 'typeof import("/Users/mradzikowski/Documents/axios-esm/node_modules/axios/index")'.

3 await axios.get('https://google.com');
```
