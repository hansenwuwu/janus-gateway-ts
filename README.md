# Janus Gateway Ts

Use latest janus version (the multistream one) client api.

## Compile janus.js

1. compile janus.js from git repo. Use below commands. (https://janus.conf.meetecho.com/docs/js-modules.html)
    Remember to use `es`.
```bash
cd ./npm
npm install
npm run rollup -- --o /path/index.js --f es
```

2. Add `adapter.js`, `adapter.min.js`, `index.d.ts` to git repo.

## Backup janus-gateway-ts by augustft
In `augustft` folder.  
https://www.npmjs.com/package/janus-gateway-ts?activeTab=readme
