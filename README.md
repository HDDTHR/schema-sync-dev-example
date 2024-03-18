# Schema Sync Development Example

This is a demonstration of how directus-schema-sync can be used for CI/Development.

Because the code that achieves this is a pull request at the moment, you'll have to build the extension before starting.

### Quick steps

1- `cd extensions/directus-schema-sync`

2- `npm install && npm run build`

3- `cd ../../`

4- `cp .env.example .env`

5- Add all the missing variables to `.env`

6- `docker compose up`