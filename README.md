create-react-app test

sudo npm run eject

sudo cnpm i cross-env

- "start": "node scripts/start.js",
+ "start": "cross-env PORT=9999 node scripts/start.js",