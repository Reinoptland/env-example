## Plan

- [x] make a .env file with our credentials (in the root of our folder)
- [x] `require('dotenv').config()` as early as possible (where is that?)
  - Or `require('dotenv').config()` in any file you use an env variable
- [x] Change our config to work with environment variables
  - Change config.json to config.js
  - add module.exports to config.js
  - use env variable process.env.DATABASE_URL_DEV
  - Change config.json in models/index to config.js
- Test
- [x] Add our .env file to .gitignore
- Add to the readme what our .env file looks like
