# nodeDB
Easy to use JSON key/value database. NodeJS version of clientDB and has the exact same features.

## Please see [clientDB](https://github.com/DoxrGitHub/clientDB) for features.

## Quick initialization:
Put `nodedb.js` in the same directory as the node.js script, add `"type": "module"` in `package.json`, and include this code:

```js
import { Client } from './nodedb.js';

let client = new Client('./database.json'); // pass a json file here
await client.set(null, null) // just make sure the db is initialized in case its empty...
```

From there, you use it the exact same way you would use clientDB.

## creds
doxr

licensed under gnu agpl v3
